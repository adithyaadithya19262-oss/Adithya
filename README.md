A Network Scanner Tool is a cybersecurity application used to scan a computer network and identify connected devices, IP addresses, open ports, and running services.
It helps network administrators and cybersecurity students understand network activity and identify possible security weaknesses.

what it does
Our Network Scanner Tool performs the following tasks:
IP Address Detection: Identifies the target device's IP address.
Host Discovery: Finds active devices connected to a network.
Port Scanning: Checks which ports are open or closed.
Service Detection: Identifies services running on open ports.
Banner Grabbing: Collects available service information.
Security Analysis: Highlights potentially risky open ports.
Scan Results: Displays the scanning results on a web page.

 Technologies used
Technology Purpose
Python Main programming language
Flask Web application
HTML Website structure
CSS Website design
JavaScript User interaction
Socket Port scanning
Kali Linux Execution environment
GitHub Project storage

Working process:
User opens the Network Scanner website.
Enters an IP address.
Clicks the Scan button.
Python starts scanning the selected ports.
The tool checks whether ports are open or closed.
Results are displayed on the website.

Step 1: Open Terminal



mkdir Network-Scanner-Tool
cd Network-Scanner-Tool


Step 2: Create a virtual environment


python3 -m venv venv
source venv/bin/activate

Step 3: Install Flask

pip install flask

Step 4: Create the Python file


nano app.py 

 

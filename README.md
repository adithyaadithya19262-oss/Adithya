
🔍 Network Scanner Tool

📌 Project Overview

The Network Scanner Tool is a cybersecurity project developed using Python. It is designed to scan a network or target IP address and identify active hosts, open ports, and available network services.

This tool helps users understand network security and identify potentially exposed ports.

🎯 Objectives

- Identify active hosts on a network.
- Scan open and closed ports.
- Detect available network services.
- Retrieve service banners when available.
- Understand basic network security concepts.

🛠️ Technologies Used

- Python 3
- Kali Linux
- Socket Programming
- Asyncio
- HTML and CSS (if using the web interface)
- Git and GitHub

⚙️ Features

- IP address scanning
- Port scanning
- Open port detection
- Service banner detection
- Network information gathering
- Simple and user-friendly interface (if enabled)

💻 Requirements

- Kali Linux or Linux operating system
- Python 3
- Git
- Basic knowledge of networking

🚀 Installation and Execution

Step 1: Clone the Repository

git clone https://github.com/YOUR-USERNAME/Network-Scanner-Tool.git

Step 2: Open Project Folder

cd Network-Scanner-Tool

Step 3: Install Requirements

pip install -r requirements.txt

Step 4: Run the Scanner

python3 scanner.py

If your project uses a Flask web interface, run:

python3 app.py

Open your browser and visit:

http://127.0.0.1:5000

📊 Sample Output

================================
      NETWORK SCANNER TOOL
================================

Target IP: 192.168.1.1

Port 21  : CLOSED
Port 22  : OPEN
Port 80  : OPEN
Port 443 : OPEN

Scan Completed Successfully!

Sample output for demonstration only.

🔐 Applications

- Network security testing
- Open port identification
- Basic cybersecurity learning
- Network administration
- Ethical hacking practice

⚠️ Disclaimer

This tool is developed for educational and ethical cybersecurity purposes only. Scan only networks and systems for which you have permission.

👨‍💻 Author

Developed as a Cybersecurity Mini Project.

Project Name: Network Scanner Tool
Platform: Kali Linux
Language: Python
Category: Cybersecurity

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

 

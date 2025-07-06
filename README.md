🛡️ Crypher Port Scanner

> A lightweight, fast, and customizable port scanner built in Python for ethical hackers, cybersecurity learners, and network testers.




---

🔍 What is Crypher?

Crypher Port Scanner is a command-line tool that scans open TCP ports on a target host. It’s designed to be simple for beginners yet powerful enough for professionals to tweak and integrate into their pentesting toolkit.


---

⚙️ Features

✅ Fast port scanning with multi-threading

✅ Custom port range input

✅ Clean output with open/closed port status

✅ Handles unreachable hosts gracefully

✅ Beginner-friendly and easy to extend



---

📸 Screenshot

$ python crypher.py -t 192.168.1.1 -p 20-100

[+] Starting Crypher Scan on 192.168.1.1
[+] Open Port Found: 22 (SSH)
[+] Open Port Found: 80 (HTTP)
Scan Complete in 2.3 seconds


---

🚀 How to Use

🔧 Requirements

Python 3.x


🐍 Installation

git clone https://github.com/0xrehan/crypher-port-scanner.git
cd crypher-port-scanner
python crypher.py -t <target-ip> -p <start-end>

🧠 Arguments

Argument	Description

-t or --target	Target IP address or hostname
-p or --ports	Port range to scan (e.g., 20-100)



---

📁 Project Structure

crypher-port-scanner/
├── crypher.py          # Main port scanner script
├── README.md           # Project documentation
├──gitignore

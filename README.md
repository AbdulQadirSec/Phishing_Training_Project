# Phishing_Training_Project
“Educational phishing simulation using Social-Engineer Toolkit (SET) for cybersecurity awareness.”
## 🎯 Objective
A training simulation of a phishing attack using the **Social-Engineer Toolkit (SET)** within **Kali Linux**, designed to raise cybersecurity awareness and demonstrate ethical testing methods.

## 🖥️ Environment
- Operating System: Kali Linux (VirtualBox)
- Tool: Social-Engineer Toolkit (SET)
- Module: Website Attack Vector → Site Cloner → Credential Harvester
- Port: 80 (HTTP)
- Local IP Address: 10.0.2.15

## 🧪 Execution Steps
1. Launch the toolkit:
   ```bash
   setoolkit
Select:

Social-Engineering Attacks
Website Attack Vector
Site Cloner

Enter the local IP address and target URL.
Run the Credential Harvester and wait for simulated data capture.

📊 Results
When test credentials were entered on the cloned page, the terminal displaye
WE GOT A HIT!
PARAM: lognForm:j_idt14=iluiiviy
PARAM: lognForm:j_idt18=uyogyvuu
A text report was generated at:
/usr/share/set/reports/

 📸 Screenshots

 1. SET Initialization in Kali Linux
![SET Initialization](Screenshot_2026-09-19_141753.png)

 2. Captured Credentials Output
![Captured Credentials](Screenshot_2026-09-19_141956.png)

Analysis
The toolkit successfully captured form data from the cloned page.
The experiment highlights the importance of verifying URLs and using HTTPS on login pages.

🛡️ Recommendations
Enable SSL/TLS on all login pages.
Train users to verify website addresses before entering credentials.
Implement threat detection systems to monitor suspicious POST requests.

⚠️ Ethical Notice
This project was conducted for educational and awareness purposes only in a controlled lab environment.
No real users or systems were targeted








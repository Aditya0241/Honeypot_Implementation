# Honeypot-Real-Time-Implementation
Created a Flask application that creates a proxy server to guard the actual server from the intruder and captures the activity, including face capture (image and video) and keylogger monitoring.<br>
Developed an IDS mechanism that informs the admins in real-time via Email, WhatsApp and Telegram, when an intrusion is detected.
<br><br>
<img src="https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/loginportal.png">
<br><br>
<img src="https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/unsuccessful%20page%20redirect.png">

## Introduction
Day by day, the number of users connecting to the internet has increased significantly, and with this rise in users comes an increase in malicious intrusions and risk. To detect these intrusions, various systems are being introduced, with honeypot being one of them. A honeypot is a trap set in computer technology to identify and detect unauthorised access to or use of sensitive data. The focus is on gathering as much information as possible about their pattern, programmes used, and purpose for attack in a quiet manner. By detecting intruders, a honeypot produces a log that refers to an intrusive operation. It also aids in the reduction of data breach threats. “A honeypot is an information system resource whose importance lies in unauthorised or illegal use of that resource,” says Lance Spitzner, founder of The Honeynet Project.
<br>
This project focuses on similar kind of structure in which we'll not only be taking the record of IP address and location but also, we will be taking the screenshots of the user's system. This device may be installed inside the network, outside of the network, or inside the DMZ. Any action taken by an intruder or attacker within the honeypot can be recorded. A honeypot can record access attempts, capture keystrokes, identify files that have been accessed and updated, and identify the programmes that have been run inside the honeypot. We can also determine an attacker's ultimate motives if he is unaware that he is inside a honeypot. A honeypot is a tightly guarded computing resource that we want probed, intruded, attacked, or compromised.

## Objective and Features
Our system aims not only to record IP addresses and locations in this project, but it will also take screenshots of the user's system so that the photos can be analysed later and the exact actions can be tracked. The honeypot's main goal is to attract hackers or attackers so that their actions can be recorded. This knowledge is extremely useful because it can be used to investigate device vulnerabilities or to research the most recent tactics used by attackers, among other things. The honeypot will be filled with enough knowledge to attract the attackers.

<br>
- Worked on the real-time implementation by recording the real-time screen shots of the suspect system, and face captures of the suspected attacker. <br>
- If we find any suspicious activity like not able to login in the portal for more than 3 times then the honeypot system will be activated in the backend which will start taking the screenshots of the intruder’s system<br>
- Logging the activity of the intruder (keylogger), and <br>
- Alert the admins via 3 important platforms: *WhatsApp*, *Telegram* and *Email*.<br><br>
<img src = "https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/captured%20image%2Bvideo.png">

<br>

## Tech Stack 
<br>
In this project, a honeypot based approach for intrusion detection/prevention systems is proposed. <br>
Language used: Python3<br><br>
Technologies:<br>
1. Flask: A web framework used to develop and integrate our honeypot backend with the web application using various tools, libraries and applications.<br>
2. Ngrok: A cross-platform application used to create a secure tunnel from a public URLto our web application running on the system.<br>
3. WhatsApp (Twilio API), Telegram & Gmail: For sending real-time alerts. <br>



## Methodology
When an attack is being performed on the system, the unusual attempts are detected through the methodology that is proposed. A very strong system is implemented in the point of Information Security Management.<br>

A honeypot like structure is implemented in which I didn’t focus on recording the IP address but worked on recording the real time screen shots of the suspect system. If we find any suspicious activity like not able to login into the portal for more than twice then the portal will start taking the screenshots of the system and these images can be studied later to know the exact activity of the user. If the consumer is found to be suspect, legal action against him or her can be taken.
<br><br>
<img src="https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/whatsapp-1.png">
<br><br>
<img src="https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/gmail-2.png">
<br><br>
<img src="https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/telegram.png">
<br><br>
<img src="https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/terminal-1.png">
<br><br>
<img src="https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/Terminal-2.png">
<br><br>
<img src="https://github.com/pranavkhuranaa/Honeypot-Real-Time-Implementation/blob/main/assets/implementation%20screenshots/Terminal-3.png">

<br><br>

## Contact Me
*Email:* pranav.khuranaa@gmail.com <br>
*LinkedIn:* https://www.linkedin.com/in/pranav-khurana




</BR> Licensed under [MIT License](LICENSE)



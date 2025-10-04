Reflective Learning Journal Template – BRG27-ISEA 

Student Name:  Chai Wei Zhe
Student ID: CT0388103
GitHub Repository Link: 
Video Walkthrough Link: 

FileName: CTID-ChaiWeiZhe-AssignmentISEA.docx  



1. Introduction 

This reflection journal is about my learning experience in the course "Introduction to Server Environments and Architectures".
Throught the 4 lessons of this course, I was introduced to the foundational concepts in relation to the server infrastructure, deployment models, and the role of servers in supporting web and network-based applications.

Refer: This reflection journal explores my learning experience in the "Introduction to Server Environments and Architectures" course. Throughout this course, I was introduced to the foundational concepts behind server infrastructure, deployment models, and the role of servers in supporting web and network-based applications. As someone developing a deeper understanding of IT systems, this course challenged me to think critically about how different server environments operate, interact, and scale. In this reflection, I will discuss key concepts that stood out, the challenges I encountered, and how this knowledge has influenced my perspective on system design and administration.


2. Linux Environment Setup and GitHub Integration 

 

GitHub Usage 

 

3. Linux Services, Permissions, and Bash Scripting 

Service Configuration and User Permissions 

Services installed (e.g., NGINX, SSH). 

Permission controls (e.g., chmod, chown, usermod). 

Lessons learned on least privilege and access control. 

Scripting and Automation 

Purpose of your script (e.g., log backup). 

Cron job setup and testing process. 

Reflection on debugging and improvements. 

 

4. Cloud Infrastructure and TCO Analysis 

Cloud Deployment 

Which platform you used (AWS/Azure/DO). 

Steps taken to configure your cloud VM securely. 

Reflection on cloud infrastructure provisioning. 

Cost Analysis 

Summary of TCO comparison across providers. 

Criteria considered (cost, flexibility, scalability). 

Your platform recommendation and why. 

 

5. DNS Setup and SSL Configuration 

DNS Management 

Domain used and DNS record configuration. 

Tools used to verify DNS propagation. 

SSL Certificate with Let’s Encrypt 

Certbot usage and challenges. 

HTTPS redirection and security headers. 

Reflection on the importance of encrypted traffic. 

 

6. Automation and Cron Jobs 

Describe cron jobs configured. 

Script improvements and error handling. 

Importance of automation in real-world environments. 

 

7. Consulting Simulation and Additional Server Service 

Peer Consultation Reflection 

Overview of your proposed solution (stack, budget, security). 

Feedback received and how you incorporated it. 

Optional Lab (Your Chosen Service) 

Service deployed (e.g., MariaDB, vsftpd, Docker). 

Configuration steps and security considerations. 

Reflection on learning a new service independently. 

 

8. Problems Encountered and Solutions 

(Create a table or list format.) | Problem | How You Solved It | |——–|——————-| | Example: SSL failure | Opened firewall and EC2 SG ports | 



9. Industry Relevance 

Which career roles this lab series relates to (SysAdmin, DevOps, etc.). 

How this experience helped build confidence in real-world skills. 

Mention any frameworks referenced (NIST, OWASP, SANS). 

 

10. Final Reflection 

Summarize your overall learning experience. 

What skills you improved. 

How you would approach future server projects differently. 

 

11. AI Tools Used (if any) 

List any AI tools (ChatGPT, Copilot) used for grammar, scripting help, etc. 

Be honest and specific. 

 

12. Appendix (Add as needed) 

Bash scripts 

Cron entries 

Screenshots 

NGINX or service config files 

GitHub repo file structure 

Lab 1A
Downloaded VMware workstation Pro and ubuntu
Installed VMware workstation Pro, created new VM Image


Lab 1B
installed apache with linux comman
Apache2 setup, able to enter web page with ipv4: 127.0.0.1

create index.html with touch function.
nano/gedit file can edit it from terminal.
once edited and save, open the file, a web page with the edited teext will be shown
closed service for apache2, tried to nmap 127.0.0.1, port 80 is not seen.
once start again, port 80 will be shown


change the permission for a file.
chmod 000 newfile, newfile cannot be open, read, write, a logo related will be shown at the side of the file
created new user: testuser




September 28



October 4
Launch Ubuntu, created a new instance, selected SSH, HTTP and HTTPS
Install Apache2 again 
Connected to http://3.107.8.103/
Go to https://www.duckdns.org/
It allows signing up with GitHub account and shares only public data.
Have to complete the reCaptcha , unable to coneect, unable to complete reCaptcha on DuckDNS
Freenorm currently unable to register free domain name.

Using GoDaddy to create the domain name, login and bought the domain name
Connect domain name with the link itself
fuck godaddy

skipping to activity 2 first

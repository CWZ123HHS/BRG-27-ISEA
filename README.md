Reflective Learning Journal Template – BRG28-ISEA 

Student Name: Chai Wei Zhe 

Student ID: CT0388103, 35900251 

GitHub Repository Link: https://github.com/CWZ123HHS/BRG_ISEA/blob/main/README.md 

Video Walkthrough Link:  



1. Introduction 


This reflection journal is about my learning experience in the course "Introduction to Server Environments and Architectures" (ISEA). 
Throughout the 4 lessons of this course, I was introduced to the foundational concepts in relation to the server infrastructure, deployment models, and the role of servers in supporting web and network-based applications. 
After going through the 4 days of lessons and lab activities, I have gained practical insights and deeper understanding of how server environments operate in real-world scenarios. 
This reflection journal will highlight the lab activities that I have done, challenges faced, and knowledge learnt. 



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

I have used the website https://www.whatsmydns.net to verify DNS propagation.

SSL Certificate with Let’s Encrypt 

Certbot usage and challenges. 

During the first time I have tried to run the certbot command, the process failed, showing "Hint: The Certificate Authority failed to verify the temporary Apache configuration changes made by Certbot. Ensure that the listed domains point to this Apache server and that it is accessible from the internet."
Then with the help of the lecturer, we manage to find out that it is A record that are named using "cweizhe22334455.online" have caused the problem.
Therefore, I deleted it and test the certbot again. This time it manage to work.
Next, I used the this link https://www.whatsmydns.net to check on the dns propagation, most of the cities have successfully recorded but some cities like Mexico City, Diemen and Antalya have failed to record. 

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

Docker?

Configuration steps and security considerations. 
Reflection on learning a new service independently. 

 

8. Problems Encountered and Solutions 

(Create a table or list format.) | Problem | How You Solved It | |——–|——————-| | Example: SSL failure | Opened firewall and EC2 SG ports | 

Unable to start up VM with VirtualBox. 

Switch to VMware Workstation. 

Failed to connect public address to domain. 

Remove other A records that were added with the Domain name. 

 

 

9. Industry Relevance 

Which career roles this lab series relates to (SysAdmin, DevOps, etc.). 

How this experience helped build confidence in real-world skills. 

Mention any frameworks referenced (NIST, OWASP, SANS). 

 

These lab series are related to career roles like System Administrator, DevOps Engineer, Linux Engineer as these types of career roles that require a strong foundation on Linux operating system.  

This experience helps me to have a better understanding of how Linux skills is important and demanding as a real-world skill as many careers in the IT field are related to it. 

 

10. Final Reflection 

1. Summarize your overall learning experience. 
2. What skills you improved. 
3. How you would approach future server projects differently. 



Overall, the lessons of this course are scheduled fast, 2 weekends in a row and there are only 4 days of lessons. It will be tough to understand that much knowledge and going through the lab activities in this period of time. I would need more time to learn and train on using the Linux commands on Ubuntu to be more familiar with it. 


During these 4 lessons, I have learnt how to use the Linux commands, permission, scripting, understand how to implement TCO to decide on the items needed to be bought, understand the how to use Amazon EC2. 


In future if I were to approach server projects, I will need to be careful on each step to configure. Mistakes like typo error can cause the entire configuration to fail more easily. It will be hard to trace back to see what the problem is, and more time and resources will be wasted on reconfiguring. I also have understood what the server will be used for to ensure the proper packages and setup to be configured. Overall, interacting with servers needs to be careful in each portion and is best to take note of what was configured. 


 

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

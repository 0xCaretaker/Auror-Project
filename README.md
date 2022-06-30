# Auror-Project
Recently, I stumbled on an initiative called "The Auror Project" by [Sudarshan Pisupati](https://www.linkedin.com/in/sudarshan-pisupati-607b0ab/) which was starting a course called "[3 Machine Labs](https://www.linkedin.com/feed/update/urn:li:activity:6919205808157155328/)". 
"3 Machine Labs" is a challenge based learning approach to solidify fundamentals of Active Directory over a series of 9 sessions. 

## Task I
The first session came with a [challenge](https://docs.google.com/document/d/1Zk_O_JpFQk5JQRGF9CAC0plml3ua3hCQ5VBDLxE2GQI/edit#heading=h.1vlpfqvcrv4) to automate the process of building an Active Directory Lab with some specifications.

Automation should:
- Setup two Virtual Machines; Windows Server & Windows 10 
- Install Active Directory Domain Services(ADDS) on the Windows Server and promote the server to Domain controller through a process called DC Promo
- Add Windows 10 machine to Windows Server domain, through a process called Domain join

Some specifications for the machines were:
For Windows Server (Domain controller):
- Domain name should be "auror.local"
- Has DNS role
- Contains a Domain user called "Adam" with password "Pass@123"

For Windows 10:
- Should've Google Chrome installed
- User "Adam" should be configured as a local administrator
- Firewall should be disabled

More details on Task I: [0xcaretaker.github.io/posts/Automation-on-the-Fly/](https://0xcaretaker.github.io/posts/Automation-on-the-Fly/)

# Work Experience Blog Post
This repository is where I will host a "blog post" detailing my internship experience developing HMI and SCADA systems.

## How it Started
During the summer months in the years 2018-2021, I worked at a company called Baycoat in Hamilton, ON as a summer student on the production line. <br> 
Baycoat is Canada's leading steel coating line. For more information about Baycoat, click here: http://www.baycoat.com/index.html <br>
During the summer of 2022, I also worked at Baycoat, but in a different role. I was approached by the Operations Manager asking if I would like to help develop some software for the company. 
I was asked because of my knowledge of the production process and my background in computer science. <br> 

## What is the Project
### Scada Systems
I was asked to develop a SCADA system that would allow management and supervision to check in on production from their office. 
Seeing the potential in the project, I fulfilled managements request as well as added information for the maintenance team to help troubleshoot mechanical and 
electrical errors. Baycoat has two production lines, so I decided to create a separate SCADA system for each production line. The SCADA systems were
developed with Visual Basic Script. Note: I cannot share the source code of the systems but I am allowed to share images of the SCADA systems. <br>
Line 3: <br>
![Line 3 Scada](/L3.PNG) <br>
Line 4: <br>
![Line 3 Scada](/L4.PNG) <br>

These are Siemens WinCC Flexible Runtimes designed for Siemens HMI screens. Here are some images 
of the development environment. <br>
![Development Environment](/TiaPortal1.PNG)
![Development Environment](/TiaPortal2.PNG)

The timeline for this project was from May 2022 to the end of August 2022. I had finished the bulk of the development for the SCADA systems by the End of June 
so I decided to take on some more projects. 
### Web-Based Dashboards
I also implemented web-based dashboards using the Siemens Information Server Platform. This platform allows developers to archive any information coming from the 
PLCs into a large SQL database. From this database, information can be pulled to create web-based dashboards that allow management to look at historical trends
of production data as well as production data in real-time.

### Auto-Generated Reporting
In addition to the SCADA System and the Dashboards, I was asked to create reports using the Siemens Information Server. Siemens has developed a plugin for 
Microsoft Excel that allows users to select data to import from the Information server, which was used to pull in data in various time ranges. These excel reports 
are auto-generated every 12-hour shift, daily, weekly, and monthly. For the weekly and monthly reports, the number of data points was often in the hundreds of thousands 
of entries. Company executives are using these reports to track production data so they can optimize their costs. I cannot post any excel files because they contain sensitive
data, but I can share some screenshots. <br>
Weekly Production Data Report
![Report](/L4CoatW.PNG)
Weekly Downtime Report
![Report](/L4DownW.PNG)
Data in Raw form
![Report](/L4Data.PNG)

## What I learned
I am very thankful to Baycoat for giving me this opportunity as I have learned so much through this process. Not only have I sharpened my technical skills, but I have 
also learned useful business skills such as presenting to company executives.
### Technical Skills
Coming from a computer science background, I had to learn a lot about electrical engineering and circuitry to work with PLCs. Before I could develop the SCADA
system, I first had to make sure I could access the information I needed from the PLCs. In order to do this, I worked with electricians to learn how to read circuit 
diagrams for complex machinery. In some cases, I needed to add new variables to the PLCs internal storage to access the data I wanted which required using the 
circuit diagrams so I could tell the PLC which wire to get information from. This aspect was daunting at first and was a steep learning curve, but also very 
rewarding because I have a completely different outlook on how machines work. In addition, I also helped electricians and automation technicians troubleshoot
electrical and PLC faults using Siemens Step 7 software. <br>
Once I had all the information I needed in the PLCs, developing the Scada Systems went by smoothly because of my programming background. This process helped me 
sharpen my front-end development skills because the Scada systems are written in Visual Basic Script. 
### Business Skills 
In addition to developing new technical skills, I also learned some important business skills. This experience taught me how to work well under pressure and meet strict deadlines.
Having only 4 months to design, develop, test and roll out such a large project seemed overwhelming at first. However, it really helped me learn how to manage
projects of large scope and meet my deadlines. I had guidance from electricians and technicians along the way, but I was the only developer on this project which 
forced me to use my time wisely and efficiently. In addition to time management skills, I also had the opportunity to participate in meetings with company executives 
such as the President of Baycoat and management. These presentations included PowerPoint shows, live demos, and discussions about the project budget. These
presentations helped grow my confidence and have prepared me for similar meetings in the future. 
## Conclusion
All in all, this experience has been the best work experience I have had so far. It has made me excited to work with software because going to work every day did not 
feel like a chore. I was excited to come to work which really helped my productivity and fueled my passion for the software industry. I have learned so many 
useful technical and business skills through this experience. I am very grateful for this opportunity. <br>
Note: For references regarding this project, please email me at matthew.r.cheverie@gmail.com and I will get you in contact with someone.

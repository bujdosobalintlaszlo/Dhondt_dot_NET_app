# Project Goal
For our school project, we were tasked with implementing a real-world system that involves data that can be visualized. We chose the D’Hondt method, a proportional representation system used for allocating seats in the European Parliament.
Previously, we had implemented a console application to solve this problem, so this project was not just about problem-solving but also refactoring and improving the code for clarity and usability.
By taking on this challenge, we were able to create a system that accurately simulates the D’Hondt allocation process and presents the results in a clear, visual format. This approach helped us gain a deeper understanding of proportional representation systems, and our work was graded with a 100% score for the project.

# Original project
It was written for console. The main logic was implemented there and test were written for all classes, making sure of the correctnes of the program. We did manual tests as well.

# Used technologies
- C# (.NET Framework 4.8)
- Windows Forms App (.NET Framework)
- NUnit

# How did we mannaged to compelte the task?
When we developed this application, we had already worked as a team before.
We knew each other’s strengths and weaknesses, which made collaboration and problem-solving much easier.
For communication, we used Discord, and for task tracking, a shared Google Drive spreadsheet.
This allowed us to organize tasks, monitor deadlines, and stay on track efficiently.

# Code structure
From the beginning, we already had a well-defined structure that didn’t change much from the previous version of the project.
Our main goal was to design it using object-oriented programming (OOP) principles, ensuring that the system remains cohesive, maintainable, and extendable, even years later, every part would still make sense and fit together naturally.
A special aspect of this project is that we made extensive use of LINQ, as we wanted to explore its capabilities and write clean, expressive, and efficient code.We also added comments and XML summaries throughout the project to make it easier to understand each class’s or function’s purpose during future development or maintenance.

# Features of the app:
(The app was mainly written to bigger screens with 16:9,16:10 aspect ratios, since there wasn't any restrictions regading that and the used platform (forms) wasn't really suted for that. Also the application is in my native language.)
<img width="1914" height="1029" alt="image" src="https://github.com/user-attachments/assets/69c989e5-9923-4430-af46-63cce61ba58d" />
The aplication is able to display:
- Number of votes
- Participants whom didn't vote
- Number of parties
- The winning party
- Winning partys votes
- Winners vote ratio
- The used testfiles name
The diagrams can display:
A table showing how the votes were calculated.
A “Mandátum arány” (Mandate Ratio) chart showing the distribution of mandates among parties.
A “Szavazatai arány” (Vote Ratio) chart showing the ratio of votes among parties.
A bar chart displaying the total number of votes received by each party.
Example:
<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/36363d86-b20e-41a6-9441-f2d910fe1e0e" />

# How to use the app?
Guide to pull the repository:
Into the cmd:
```
git init
git remote add origin https://github.com/bujdosobalintlaszlo/Dhondt_dot_NET_app
git checkout -b main
git pull origin main
```
Here you will find an .exe which you can run.
The app it self has 2 modes.
- You can use your own txt-s (which I provided in the repository or you can create your own based on those).
- You can generate one in the app with the generate button.
Step by step guide for the 1. option:
1. Press on file kivalasztasa
2. From the repositorys folder choose a .txt
3. After that you need to press ok, and it will display.
4. If you want to clear the app, simply press "torles".
Step by step for the second one:
1. Press on "generalas", and you will be able to set your own values between the bounds which the application has:
<img width="558" height="254" alt="image" src="https://github.com/user-attachments/assets/c38f5a95-88d2-4db4-9e30-d5a2b8f7dda3" />

2. Press "Generalas" and it will be displayed.

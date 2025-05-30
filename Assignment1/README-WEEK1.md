# Software-Assurance
Software Assurance course - Summer '25.

**Types of Version Control Systems — What type is Git?**

There are mainly 3 types of version control systems:

Local VCS – tracks changes only on your own computer.

Centralized VCS (CVCS) – there's one main server; everyone connects to that to get or update code.

Distributed VCS (DVCS) – everyone has a copy of the whole project including history.

Git is a distributed version control system. That means I can work offline, commit changes, and later sync them with a remote (like GitHub).

📸 **Snapshots**


Git doesn’t just track changes line by line. It actually takes a picture (a “snapshot”) of your project at every commit. If a file hasn’t changed, Git just links it to the old version instead of saving it again. So it’s fast and smart.

📦 **What is a Repository? **(Remote vs Local)


A repository is like a folder that stores everything — files, changes, history.

Local repo: lives on my computer (it’s the .git folder inside the project).

Remote repo: a shared version online (like on GitHub). It’s how we collaborate with others.
![Alt text](diagram3-1.png)

💾 **What is Commit?**


When I say git commit, I’m saving a version of my project. It’s like telling Git: “Hey, I’m happy with these changes — save them!” Commits are permanent and track who made what change and when.
![Alt text](diagram4-1.png)

💻 W**hat is WorkingDirectory?**


This is the folder I’m actually working in — like on VS Code. I make changes here. Git keeps track of what’s modified.

📥 **What is Staging Area?**

Before I save changes with a commit, I add them to the staging area using git add. It’s like packing things in a box before sealing it with a commit. I get to choose what goes in.
![Alt text](diagram2-1.png)

🗺️ **Diagram of Git Architecture & Flow**


Here’s a simple diagram that shows how everything connects:
![Alt text](diagram1-1.png)

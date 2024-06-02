6XV - Project Overview 🖥️
Description
This project introduces students to the structure and implementation of the 6XV operating system. Through hands-on tasks, users will learn about system calls, data structures, and practical aspects of building and running an operating system.

What I Learned 📚
Throughout the development of this 6XV operating system project, several key concepts and skills were reinforced:

Understanding 6XV Operating System: Gained in-depth knowledge about the architecture and components of the 6XV OS.

System Calls Implementation: Learned how to implement and manage system calls within the OS.

Data Structures: Explored various data structures used in the 6XV OS and understood their significance.

Adding New System Features: Developed skills to extend the OS by adding new system calls and commands.

Problem Solving: Enhanced analytical thinking and problem-solving skills by overcoming constraints and limitations in the project.

State Management: Learned the importance of state management in operating systems by tracking and modifying system states.

Project Documentation: Improved documentation skills by organizing and writing clear, coherent README and project documentation.

Objectives 🎯
Familiarize with the 6XV operating system.
Understand the practical implementation of system calls.
Explore different data structures used in an operating system.
Add a new system call.
Implement a new system command (ps) to display the status of processes.
Gain hands-on experience in building and running an operating system.
Approach 🚀
The solution path for this project is slightly different from standard tutorials:

Do not modify h.syscall file: Understand the role of relevant data structures in the c.syscall file (lines 112-134) and find a workaround for the limitation.
Make changes in S.usys file: Implement the necessary changes (additions) in the S.usys file to support the new system call and command.
Features ✨
System Components:
System Call Addition: Add new system calls to extend the OS functionality.
Command Implementation: Implement the ps command to display the status of processes in the system.
Key Files:
h.syscall: Header file with system call declarations (must not be modified).
c.syscall: Contains data structures and system call implementations (focus on lines 112-134).
S.usys: The file is to be modified to add new system calls and commands.
Installation 💾
Clone the repository to your local machine:

git clone https://github.com/yourusername/6XV-operating-system.git
Navigate to the project directory:

cd 6XV-operating-system
Usage 🛠️
Understand the existing code: Familiarize yourself with the codebase and project structure.
Implement changes: Add new system calls and commands as outlined in the project objectives.
Compile and run the OS: Build and test the operating system to ensure all new features are correctly implemented.
Contribution 🤝
To contribute to this project, follow these steps:

Fork the repository: Create a fork of this repository.
Create a new branch: Create a feature branch for your changes.
git checkout -b feature/new-feature
Commit your changes: Make and commit your changes with descriptive messages.
git commit -m "Add new system call and ps command"
Push to the branch: Push your changes to your forked repository.
git push origin feature/new-feature
Create a pull request: Open a pull request to merge your changes into the main repository.

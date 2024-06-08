[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15242209&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
    Currently I am using windows 10 OS. The screenshots will be of windows 10 while the description applies to both windows 10 and windows 11.
      The prerequisites needed are:
      Windows 11 installed in your computer.
     A stable internet connection
     A disk space to hold the software
     Administraror priviledges to be able to install the software.

     Steps needed to download and install:
Visit the official website: Go to Visual Studio Code.
Download the installer: Click on the "Download for Windows" button to get the installer.
Run the installer: Once downloaded, run the installer (VSCodeSetup.exe).
Setup Wizard: Follow the prompts in the setup wizard.
Accept the agreement.
Choose the installation location.
Select additional tasks such as creating a desktop icon and adding to the PATH environment variable (recommended).
Complete the installation: Click "Install" and then "Finish" to complete the setup.
![img_2](https://github.com/Powerlearnproject/se-assignment-5-Hillcest/assets/106829161/f433a7bb-3190-4b8b-b044-307884e6d692)
![img_1](https://github.com/Powerlearnproject/se-assignment-5-Hillcest/assets/106829161/b0af82be-12d6-4d5e-a7d7-acef9de2e4c4)
![img_3](https://github.com/Powerlearnproject/se-assignment-5-Hillcest/assets/106829161/a1da4e04-0fb3-4ae3-afbe-2b775fe0b026)


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
     The initial essential extensions include:
     Prettier- to better organize your code for readability.
     Python - When you are working with your python
     LiveServer - To automatically reload the web application during development.
     WakaTime - To tarck the total time you spent on coding.It is not essential but advisable to have.

     One can adjust the color theme, font-size to be used within the app.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
     The main components of the VS code interface are: Activity Bar, Side Bar, Editor Bar and Status Bar.
  
     Activity Bar: Located on the far left, it allows one to switch between different views such as Explorer, Search, Source Control, Run and Debug, and Extensions.
     Side Bar: Displays the content of the selected activity from the Activity Bar, like the file explorer.
     Editor Group: The central area where you write and edit your code. It supports multiple tabs.
     Status Bar: Located at the bottom, it provides information about the opened project and the status of your code.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
     The Command Palette is a tool in VS Code that allows you to access various commands and settings.
     Access: Press Ctrl+Shift+P.
Common Tasks:
Open Settings: Preferences: Open Settings
Install Extensions: Extensions: Install Extensions
Select Interpreter: Often used when coding with python which requires virtual eb=nvironment.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
  
     Role of Extensions:
     Extensions enhance the functionality of VS Code by adding new features or integrating tools that makes life easier for the developer.
     
     How to Find, Install, and Manage Extensions:
     Find Extensions: Click the Extensions view icon in the Activity Bar or press Ctrl+Shift+X.
     Install Extensions: Search for the desired extension and click "Install".
     Manage Extensions: Disable, uninstall, or configure installed extensions through the Extensions details view.
     
     Essential Extensions for Web Development:
     LiveServer
     HTML CSS Support
     JavaScript (ES6) code snippets
     Debugger for Chrome

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
  
     How to Open and Use:
     Open Terminal: View > Terminal or press Ctrl+ ` (backtick).
     Use Terminal: Execute commands just as you would in any external terminal such as cmd.
     
    Advantages:
    No need to switch between applications as it is convenient.
    Direct access to project files and VS Code features as it is an integrated environment.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
  
     How to Create, Open, and Manage:
     Create: Right-click in the Explorer view and select New File or New Folder.
     Open: Double-click a file in the Explorer.
     Manage: Drag and drop files to organize, use Ctrl+P to quickly open files.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
  
     Customization:
     Settings Location: File > Preferences > Settings or press Ctrl+,.
     Examples:
     Theme: Preferences: Color Theme
     Font Size: Search for "Font Size" and adjust it.
     Keybindings: File > Preferences > Keyboard Shortcuts

     ![img_4](https://github.com/Powerlearnproject/se-assignment-5-Hillcest/assets/106829161/f6bc3ed4-c163-4ed1-89ae-184a15247f2b)
![img_5](https://github.com/Powerlearnproject/se-assignment-5-Hillcest/assets/106829161/437767bf-cd24-400f-b2b3-1a4cce88d003)


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
  
     Steps to Set Up and Start Debugging:
     Open a file to debug: For example, a JavaScript file.
     Set breakpoints: Click in the gutter next to the line number.
     Start Debugging: Run > Start Debugging.
     
     Key Debugging Features:
     Watch Variables: Monitor variable values.
     Call Stack: View the call stack.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
   
      Integrating Git:
Initialize Repository: Source Control view > Initialize Repository.
Making Commits: Stage changes and commit with a message.
Pushing Changes to GitHub:
Connect to GitHub: Use Git: Add Remote in the Command Palette.
Push Commits: Source Control view > Push or use the terminal with git push.


References: Visual Studio Code App.


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 


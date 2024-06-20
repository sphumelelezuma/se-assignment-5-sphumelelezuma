[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15307832&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

Download the Visual Studio Code installer for Windows.
Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). This will only take a minute.
By default, VS Code is installed under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code.(visual studio code)

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

VS Code provides both Windows user and system level setups.
The user setup does not require Administrator privileges to run as the location will be under your user Local AppData (LOCALAPPDATA) folder. Since it requires no elevation, the user setup is able to provide a smoother background update experience. This is the preferred way to install VS Code on Windows.(visual studio code)

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

The user interface is divided into five main areas:

Editor - The main area to edit your files. You can open as many editors as you like side by side vertically and horizontally.
Primary Side Bar - Contains different views like the Explorer to assist you while working on your project.
Status Bar - Information about the opened project and the files you edit.
Activity Bar - Located on the far left-hand side. Lets you switch between views and gives you additional context-specific indicators, like the number of outgoing changes when Git is enabled. You can change the position of the Activity Bar.
Panel - An additional space for views below the editor region. By default, it contains output, debug information, errors and warnings, and an integrated terminal. The Panel can also be moved to the left or right for more vertical space. (visual studio code)

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

The Command Palette provides access to many commands. You can run editor commands, open files, search for symbols, and see a quick outline of a file, all using the same interactive window. Here are a few tips:

Ctrl+P enables you to navigate to any file or symbol by typing its name
Ctrl+Tab cycles you through the last set of files opened
Ctrl+Shift+P brings you directly to the editor commands
Ctrl+Shift+O enables you to navigate to a specific symbol in a file
Ctrl+G enables you to navigate to a specific line in a file (visual studio code)

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   You can browse and install extensions from within VS Code. Bring up the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of VS Code or the View: Extensions command (Ctrl+Shift+X).
   This will show you a list of the most popular VS Code extensions on the VS Code Marketplace.
   To install an extension, select the Install button. Once the installation is complete, the Install button will change to the Manage gear button
   VS Code makes it easy to manage your extensions. You can install, disable, update, and uninstall extensions through the Extensions view, the Command Palette (commands have the Extensions: prefix) or command-line switches.(visual studio code)

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

You can open a terminal as follows:

From the menu, use the Terminal > New Terminal or View > Terminal menu commands.
From the Command Palette (Ctrl+Shift+P), use the View: Toggle Terminal command.
In the Explorer, you can use the Open in Integrated Terminal context menu command to open a new terminal from a folder.
To toggle the terminal panel, use the Ctrl+` keyboard shortcut.
To create a new terminal, use the Ctrl+Shift+` keyboard shortcut.

Advantages:
VS Code's terminal has additional functionality called shell integration that tracks where commands are run with decorations on the left of a command and in the scrollbar.
The integrated terminal can use various shells installed on your machine, with the default being pulled from your system defaults. Shells are detected and presented in the terminal profiles dropdown. (visual studio code)

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

The Explorer is great for navigating between files when you are exploring a project. However, when you are working on a task, you will find yourself quickly jumping between the same set of files. VS Code provides two powerful commands to navigate in and across files with easy-to-use key bindings.

Hold Ctrl and press Tab to view a list of all files open in an editor group. To open one of these files, use Tab again to pick the file you want to navigate to, then release Ctrl to open it. (visual studio code)

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

  Use the Settings editor to review and change VS Code settings. To open the Settings editor, navigate to File > Preferences > Settings. Alternately, open the Settings editor from the Command Palette (Ctrl+Shift+P) with Preferences: Open Settings or use the keyboard shortcut (Ctrl+,). (visual studio code) 

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

VS Code has built-in debugging support for the Node.js runtime and can debug JavaScript, TypeScript, or any other language that gets transpiled to JavaScript.

For debugging other languages and runtimes (including PHP, Ruby, Go, C#, Python, C++, PowerShell and many others), look for Debuggers extensions in the VS Code Marketplace or select Install Additional Debuggers in the top-level Run menu.

One of the key features of Visual Studio Code is its great debugging support. VS Code's built-in debugger helps accelerate your edit, compile, and debug loop. (visual studio code)


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

To use Git and GitHub in VS Code, first make sure you have Git installed on your computer. If Git is missing, the Source Control view shows instructions on how to install it. Make sure to restart VS Code afterwards.

To initialize a new local Git repository:
Pick an existing or new folder on your computer and open it in VS Code.
In the Source Control view, select the Initialize Repository button.
This creates a new Git repository in the current folder, allowing you to start tracking code changes.
This action is equivalent to running git init on the command-line.

git add .
git commit -m "pass a message of what changes you made"
git remote add origin <github repo url>
git push -u main or git push -u master depending on the name of your branch

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 


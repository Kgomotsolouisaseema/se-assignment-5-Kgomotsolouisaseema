[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292089&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   1.a Ensure your systems meets the following requirements: 
   * A modern 64-bit processor
   * at leadt 1GB of RAM
   * at least 200Mb of Free disk space 

   1.b Ensure that you have the right administration rights to install software
   1.c Installation : 
      - download Visual Studio Code  from the browser
      - click on the Operating system you Pc has and download . 
      - once downloaded , double click or right click and open the downloaded file 
      - Run the installer 
      - Accept the license agreement , the check the box that says "I accept the agreement" and click next . 
   
   1.d Select Additional Tasks 
      - this is where you can select whether you want to create a desktop icon , add to PATH , and other features you would like to have added on the  Visual Studio IDE. 
   
   1.e Ready to install : 
     - click on next 
     - once finished installing , click  finish and VS code will launch 


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   - very important setup steps after install : 
    1, navigate to file and locate the auto save button , make sure its clicked 
    2, you can change the theme to dark for your preference
    3, you can add extentions for your preference (dart ,python ,flutter,  prettier code ect )

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   3.a Activity Bar
    Location : far left side of the window
    Purpose : Allows you switch between different views or activities such as Exlplorer ,Search ,Source Control , Run and Debug , Extensions ext . each icon represents a specific activity .
   
   3.b Side Bar 
    location : Immediately to thr RIGHT of the activity bar 
    Purpose : the side bar show the context of the information related to the activity youre in . e.g extensions icon , the side bar will show the different extensions that youve downloaded and other ones , or the extension youre searching for. 
     - Explorer view : Displays the folder structure and files of your project.
     - Search View : Allows you to search across files in your project
     - Source Control View : Provides tools for version control integration.
     - Run and Debug : Offers debugging controls and displays breakpoints, call stack, variables, etc.
     - Extensions:  Lists installed extensions and allows you to search for and install new ones.

   3.c Status Bar 
    Location : The central area of the interface. 
    Purpose : This is where you write and edit your code, you can open several editors , side by side 

   3.d Status Bar 
    Location: Bottom of the window 
    Purpose : provides information about the current state of your workspace and activity file . the activity bar displays details like: 
     - line and colomn Number : indicates the cursor position in the current file 
     - language mode : Displays the programmng language of the currently active file and allows you to change it .
     - Notification Indicators : Alerts you to problems,errors and other important messages. 


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   
   # COMMAND PALETTE IN VSCODE 
    - Feature that provides quick access to various commands and functionality within the editor, it allows users to execute without navigating through menus. 

    # COMMON TASKS USING COMMAND PALETTE
     1. Search for commands 
     2. opening files : type `>` followed by file name to quickly open in the workspace. 
     3. Running Extensions : i.e type thename of the ext and run it 
     4. Git commands : git clone to clone a repo , git pull , or git commit 
     5. Debugging : command palette can be used to debug 
   

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   # ROLE OF EXTENSIONS IN VSCODE 
   Extensions in visual studio play a crucial role in enhancing and customizing the editors functionality to suit various development needs. it allows users to  add features , tools and intergrations that arent included in the base installation of VS code . 

   # COMMON EXTENTIONS FOR WEB DEVELOPMENT 
    A. Prettier - code formatter 
    B. ESLINT - Integrates ESLint into VS CODE for identifying and fixing javascript and typescript code issues 
    C. HTML Snippets  - provides a rich set of HTML5 snippets 
    D. PATH intellisense - Auto complete filenames ,providing suggestions for file paths 
    E. REST Client -enables you to send HTTP requests and view responses directly within VS CODE , useful for testing APIs

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   # Ways to open the intergrate terminal 
    1. keyboard shortcut 
     - Press Ctrl+`` (backtick) or Ctrl+Shift+` (backtick) (on Windows/Linux)
     - Press Cmd+`` (backtick) or Cmd+Shift+` (backtick) (on macOS) 
    2. Menu Navigation 
     - Go to View > Terminal in the top menu.
    3. Command Palette 
     - Open the Command Palette with Ctrl+Shift+P (or Cmd+Shift+P on macOS).
     - Type Toggle Integrated Terminal and select it from the list. 

   # Advantages of using the intergrated Terminal Compared to an External Terminal 
    1. makes workflow easier because you dont have to leave VS CODE to use terminal 
    2. automatically opens the context of the workspace you are working on,meaning you dont have to navigate to project manually 
    3. The integrated terminal ensures a consistent environment setup across different machines as part of your VS Code configuration, which is beneficial for teams.
    4. Integrate with VS Code tasks to automate common development workflows. For example, you can set up tasks to run build commands, lint code, or start a server, and then execute these tasks from the terminal.
jgfhgfhgfhg

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   #  Creating files andflders using the Explorer View 
   1.  Create a file : 
    - Open explore view by clicking thr explorer icon or press `Ctrl+Shift+E`.
    - click the "new file " icon (piece of paper with aplus sign icon) at the top of the explorer pane
    -  enter the name of the new file and press "Enter"

    2. Create a folder 
     - click on the "new file" icon (a foldr with plus sign)at the top of the explorer pane. 
     - enter thename of the new folder and press "enter". 
    
    # Opening files and folders 
     - Opening a file : double click on the file on the file explorer and open it in the editor
     - Opening a folder :
        -  click "file" > open folder' from the top menu or press 'ctrl+k+O'  
        - Navigate to the desired flder in te dislog and clck the "selected folder ". 
      
   # Managing files and folders 

   1. Renaming : 
     - right-click on a file or folder in the explorer and select rename or press 'f2'.
     - enter name and press enter.

   2. Deleting : 
     - Right-click on a file or folder in the explorer view and select the "Delete".
     - Confirm deletin when/if prompted .
   
   3. Moving 
     - Drag a file or folder from 1 location to another location in the explorer view 
     - or right-click and cut the file/folder and then paste it at desired location 


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   # ANSWER
   - users can find and customize settings in vs code by navigating to the command palette or clicking on "file" > preferences and settings , click on the setting you want to change then change it there . 
   -  Click on "view" > command palette and type preference and the setting you want to change (ie: keybinding , color theme ect . )
   - Screenshots are added for visual representation .



9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
    cite : https://code.visualstudio.com/docs/editor/debugging 
   # STEPS TO SET UP DEBUGGING
   1. install required extension 
   2. configure launch configuration
   3. Modify or create 'launch.json'
   4. Start debugging : 
     - set breakpoints : open file you want ot debug ,
     - click in the gutter next to the line number where you want to set a breakpoint(a red dot appears)
   5. interact with the debugger : 
     - the debugger will pause at the breakpoints you set , allowing you to inspec variables, step through code and analyze program flow. 

   # Key debugginh features in VS CODE 
    1. Breakpoints  :  Set breakpoints to pause execution at specific lines of code for inspection.
    2. Watch and Variables :  Monitor variables in the Watch panel or inline while debugging to track their values and states.
    3. Call stack :  View the call stack to see the hierarchy of function calls leading up to the current breakpoint.
    4. Step Controls
    5. Debug Console
    6. Conditional Breakpoints
    7. Exception Handling  


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

   # intergrating Git with VScode 
   1. Installing Git : 
     - ensure that Git is installed on your machine , https://www.git-scm.com/ 
     - after downlaoded , open cmd and run as admin and run these commands to connect your github to your local machine : 
          * git config --global user.name "Your Name"
          * git config --global user.email "your.email@example.com"
   
   2. Open a project in VS code : 
      - Open and folder or create a folder 

   3. Initialize Git Repository
   - first on your github UI , Create a new repository 
   - open the folder you created in step 2 and type these commands in the cmd,git bash or terminal 
   - git init: initialize the repository 
   - git add README.md : this command adds a README file but you can just "git add . " to add changes 
   - git commit -m "first commit" : this commands commits/marks the place you made changes with a comment/message . 
   - git branch -M main : This commands commits the changes to the main branch if you have not created any branches yet . 
   - git remote  add origin   https://github.com/Kgomotsolouisaseema/AssignmentTest.git : 
       * This command connects your local Git repository to a remote repository hosted on GitHub at `https://github.com/Kgomotsolouisaseema/AssignmentTest.git` , labeling it as "origin" for future reference
   - git push -u origin main 
       * This command pushes the local commits to the remote repository named "origin" on the branch named "main", setting up tracking so future git push commands can be used without specifying the remote branch.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 


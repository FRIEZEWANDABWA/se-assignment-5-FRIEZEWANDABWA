[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281265&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 


The first process of using visual studio is to Download Visual Studio:
Visit the Visual Studio website and click on "Download Visual Studio."
![download](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/vs%20search.png)
Follow the on-screen instructions to download the installer.
![download](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/download.png)
![download]()

. Run the Installer:
![download](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/vs%20run.png)
Run the downloaded installer.
![download](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/setup.png)
Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.
. Select Workloads and Components:
In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development."
Modify Installation (Optional):
![download](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/modification.png)
If needed, you can customize the installation by clicking on the "Individual components" tab in the installer and selecting or deselecting specific components.
Install:
Click the "Install" button to start the installation process.
This may take some time, as it involves downloading and installing the selected components.
Launch Visual Studio:
![download](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/launch.png)
Once the installation is complete, launch Visual Studio.
Sign in with your Microsoft account or create one if prompted.
![download](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/choose%20screen.png)
Choose Development Environment:
On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.
Start Coding:
You're now ready to start coding! Create a new project or open an existing one to begin your development work.
after launching the application you can create a folder
![create a folder](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/vs%20create%20folder.png)

Then you can rename that file that you have already

![rename a folder](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/vs%20emane%20file.png)

You can also download extra extension to help you with the cording process
![downloa d extensions](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/vs%20download%20extension.png)

You can also create a specifile file like a python document to assist you with thwe coding process
![downloadcreate python file](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/vs%20create%20py%20fil.png)
Inside the file you can have a sample code, which you can try to un it so as to see the output

![create hello file](https://github.com/FRIEZEWANDABWA/se-assignment-5-FRIEZEWANDABWA/blob/5d01bbd11a485a98afce79965069419dfbdc8438/vs%20test%20hello%20world.png)


First-time Setup
After installing Visual Studio Code (VS Code), there are several initial configurations and settings you should adjust to create an optimal coding environment:

Install Key Extensions:

Python: For Python development.
ESLint: For JavaScript linting.
Prettier - Code Formatter: For consistent code formatting.
Live Server: For a local development server with live reload.
GitLens: Enhances Git capabilities within VS Code.
Configure Settings:

User Settings: Go to File > Preferences > Settings (or press Ctrl + ,) to adjust user settings.
Theme: Choose a theme via File > Preferences > Color Theme or Ctrl + K, Ctrl + T.
Font Size: Adjust in the settings under Editor: Font Size.
Tab Size: Configure Editor: Tab Size for consistent indentation.
Set Up Keybindings:

Customize keybindings via File > Preferences > Keyboard Shortcuts.
Workspace Settings:

Configure workspace-specific settings for project-specific needs.

User Interface Overview
Activity Bar:

Located on the far left side, the Activity Bar provides access to different views such as Explorer, Search, Source Control, Run and Debug, and Extensions.
Side Bar:

This is where the contents of the selected activity bar item are displayed, like the file explorer, search results, or source control information.
Editor Group:

The central area where you open and edit your files. You can have multiple editor groups to split the view horizontally or vertically.
Status Bar:

Located at the bottom, the Status Bar shows information about the opened project and active file, like the current branch in version control, line number, language mode, etc.

Command Palette
The Command Palette is a powerful tool in VS Code that allows you to access various commands and features quickly.

Accessing the Command Palette: Press Ctrl + Shift + P or F1.
Common Tasks:
> Open File: Quickly open a file.
> Git: Clone: Clone a repository.
> Format Document: Format the current file.
> Install Extensions: Access the extensions marketplace.
Extensions in VS Code
Extensions enhance the functionality of VS Code by adding support for new languages, debuggers, and tools.

Finding Extensions:

Access the Extensions view by clicking the Extensions icon in the Activity Bar or pressing Ctrl + Shift + X.
Installing Extensions:

Search for the desired extension and click the install button.
Managing Extensions:

Manage installed extensions through the Extensions view, where you can disable or uninstall them.
Essential Extensions for Web Development:

HTML/CSS Support: HTML, CSS, and JavaScript snippets.
Debugger for Chrome: Debug JavaScript code running in the browser.
REST Client: Make HTTP requests directly from the editor.

Integrated Terminal
Opening the Terminal:

Open the integrated terminal with Ctrl + or via View > Terminal.
Using the Terminal:

You can run command-line tools and scripts directly within the editor, benefiting from the context of your project.
Advantages:

Consistent environment with the editor.
Easily switch between terminal and code.
Support for multiple terminal instances.
File and Folder Management
Creating Files and Folders:

Use the Explorer view in the Side Bar. Right-click in the file explorer and select "New File" or "New Folder".
Opening Files and Folders:

Drag and drop files into the editor or use File > Open File or File > Open Folder.
Navigating Between Files:

Use Ctrl + P to quickly open files by name.
Use Ctrl + Tab to switch between open files.
Use breadcrumbs and the Explorer view for navigation.
Settings and Preferences
Accessing Settings:

Open settings via File > Preferences > Settings or Ctrl + ,.
Changing Theme:

Go to File > Preferences > Color Theme or use the Command Palette (Ctrl + Shift + P) and type Color Theme.
Adjusting Font Size:

Change Editor: Font Size in the settings.
Customizing Keybindings:

Access File > Preferences > Keyboard Shortcuts to modify keybindings.
Debugging in VS Code
Setting Up Debugging:

Open the Run and Debug view in the Activity Bar.
Create a launch configuration by clicking the gear icon and selecting your environment.
Starting Debugging:

Set breakpoints by clicking in the gutter next to the line numbers.
Start debugging by pressing F5.
Key Debugging Features:

Breakpoints, step through code, watch variables, and view call stacks.
Using Source Control
Integrating Git:

VS Code has built-in Git support. Access it via the Source Control view in the Activity Bar.
Initializing a Repository:

Click the Initialize Repository button in the Source Control view.
Making Commits:

Stage changes by clicking the + icon next to files.
Write a commit message and press Ctrl + Enter to commit.
Pushing Changes to GitHub:

Open the Command Palette (Ctrl + Shift + P) and run Git: Add Remote.
Enter the repository URL.
Push changes using Git: Push.


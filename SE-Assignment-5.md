# SE-Assignment-5: Installation and Navigation of Visual Studio Code (VS Code)

## Installation of VS Code

### Steps to Download and Install Visual Studio Code on Windows 11

1. Go to the [Visual Studio Code website](https://code.visualstudio.com/).
2. Click on the "Download" button for Windows.
3. Once the installer is downloaded, run it.
4. Follow the installation wizard steps:
   - Accept the agreement.
   - Choose the installation location.
   - Select additional tasks (e.g., creating a desktop icon).
5. Click "Install" to complete the installation.

#### Prerequisites
- Ensure you have administrative privileges to install software.
- Verify that your system meets the minimum requirements for VS Code.

## First-time Setup

### Initial Configurations and Settings for Optimal Coding Environment

- **Theme:** Go to `File > Preferences > Color Theme` to select a theme.
- **Font Size:** Open settings with `Ctrl+,`, then search for "Font Size" and adjust it.
- **Extensions:** Install important extensions:
  1. Go to the Extensions view (`Ctrl+Shift+X`).
  2. Search for and install extensions like "Prettier - Code formatter", "ESLint", or "Python".

## User Interface Overview

### Main Components of the VS Code User Interface

- **Activity Bar:** Located on the far left, it lets you switch between views like Explorer, Search, Source Control, Run and Debug, and Extensions.
- **Side Bar:** Displays different views and panels depending on the selected activity (e.g., file explorer, search results).
- **Editor Group:** The main area where you edit your code files. You can open multiple files in tabs or split the editor to view files side-by-side.
- **Status Bar:** Located at the bottom, it shows information about the current file, such as encoding, line endings, language mode, and Git branch.

## Command Palette

### What is the Command Palette and How to Access It

- The Command Palette (`Ctrl+Shift+P` or `F1`) is a powerful tool that lets you access all available commands in VS Code.

### Examples of Common Tasks

- Open settings (`Preferences: Open Settings`).
- Install extensions (`Extensions: Install Extensions`).
- Run tasks (`Tasks: Run Task`).

## Extensions in VS Code

### Role of Extensions

- Extensions add functionality to VS Code, such as language support, themes, and tools for specific workflows.

### Finding, Installing, and Managing Extensions

- Go to the Extensions view (`Ctrl+Shift+X`), search for extensions, and click "Install".
- Manage installed extensions from the same view (enable, disable, uninstall).

### Examples of Essential Extensions for Web Development

- "Live Server"
- "Debugger for Chrome"
- "JavaScript (ES6) code snippets"

## Integrated Terminal

### Opening and Using the Integrated Terminal

- Open the terminal with `` Ctrl+` ``, or go to `View > Terminal`.
- Use it to run shell commands, scripts, and manage version control without leaving VS Code.

### Advantages Over External Terminals

- Integrated experience, context-aware, can open multiple terminal instances, split terminals.

## File and Folder Management

### Creating, Opening, and Managing Files and Folders

- Use the Explorer view to navigate your project files.
- Right-click in the Explorer to create new files or folders.
- Open files by clicking on them or using `Ctrl+P` to quickly search and open files.

### Efficient Navigation

- Use keyboard shortcuts like `Ctrl+Tab` to switch between open files, `Ctrl+P` for quick file search, and `Ctrl+Shift+E` to focus on the Explorer.

## Settings and Preferences

### Finding and Customizing Settings

- Open settings with `Ctrl+,` or go to `File > Preferences > Settings`.
- Change themes, font size, and keybindings through the settings UI or directly in the `settings.json` file.

### Examples

- Change theme: `File > Preferences > Color Theme`.
- Change font size: `File > Preferences > Settings`, then search for "Font Size".
- Customize keybindings: `File > Preferences > Keyboard Shortcuts`.

## Debugging in VS Code

### Setting Up and Starting Debugging

- Open a project folder.
- Go to the Run view (`Ctrl+Shift+D`), add a configuration by clicking on "create a launch.json file".
- Set breakpoints by clicking in the gutter next to the line numbers.
- Start debugging by pressing `F5`.

### Key Debugging Features

- Breakpoints, watch expressions, call stack, variable inspection, step over, step into, step out.

## Using Source Control

### Integrating Git with VS Code

- Open the Source Control view (`Ctrl+Shift+G`).
- Initialize a repository: Click on "Initialize Repository".
- Making commits: Stage changes, add a commit message, and commit.
- Pushing changes to GitHub: Connect to a GitHub repository, and push your commits (`Ctrl+Shift+P`, then `Git: Push`).


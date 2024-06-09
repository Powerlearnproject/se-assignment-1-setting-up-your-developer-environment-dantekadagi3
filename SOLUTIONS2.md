SETTING UP VSCODE AND PYTHON
 1) Install Visual Studio Code (VS Code)

 Step-by-Step Guide to Download and Install Visual Studio Code

1. Download Visual Studio Code:
   - Open your web browser and go to the [Visual Studio Code Download page](https://code.visualstudio.com/Download).
   - Click on the "Windows" button to download the installer for Windows.

2. Run the Installer:
   - Locate the downloaded installer file (`VSCodeUserSetup-{version}.exe`) in your Downloads folder and double-click it to run the installer.
   - Click "Next" on the setup wizard welcome screen.

3. Accept the License Agreement:
   - Read the license agreement and, if you agree, check the "I accept the agreement" box.
   - Click "Next" to proceed.

4. Choose the Installation Location:
   - Choose the destination folder where you want to install Visual Studio Code. The default location is usually fine.
   - Click "Next."

5. Select Additional Tasks:
   - Choose additional tasks you would like the installer to perform. These options might include:
     - Creating a desktop icon.
     - Adding "Open with Code" actions to Windows Explorer file context menus.
     - Registering Code as an editor for supported file types.
     - Adding to PATH (this is useful for command-line operations).
   - Click "Next."

6. Install Visual Studio Code:
   - Click "Install" to begin the installation process.

7. Complete the Installation:
   - Once the installation is complete, ensure the "Launch Visual Studio Code" checkbox is checked.
   - Click "Finish" to close the installer and launch Visual Studio Code.

 Initial Setup After Installation

1. Select a Color Theme:*
   - When you first launch VS Code, you'll be prompted to select a color theme. Choose a theme you like.

2. Install Recommended Extensions:
   - Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or pressing `Ctrl+Shift+X`.
   - Search for and install essential extensions like:
     - Python: Provides language support for Python.
     - Prettier - Code formatter: Automatically formats your code.
     - ESLint: Integrates ESLint into VS Code for JavaScript/TypeScript linting.

3. configure Settings:
   - Open the settings by clicking the gear icon in the bottom left corner and selecting "Settings," or press `Ctrl+,`.
   - Adjust settings such as font size, tab size, and auto-save according to your preferences.

2) Install Necessary Programming Languages and Runtimes

Step-by-Step Guide to Install Python

1. Download Python:
   - Open your web browser and go to the [Python official website](https://www.python.org).
   - Click on the "Downloads" menu and select "Download Python" for Windows. The latest version will be highlighted.

2. Run the Installer:
   - Locate the downloaded installer file (`python-{version}.exe`) in your Downloads folder and double-click it to run the installer.
   - At the start of the installation process, make sure to check the box that says "Add Python to PATH." This will make it easier to run Python from the command line.
   - Click "Install Now."

3. Complete the Installation:
   - The installer will copy files and set up Python on your computer. This may take a few minutes.
   - Once the installation is complete, click "Close."

4. Verify Installation:
   - Open Command Prompt or PowerShell.
   - Type `python --version` and press Enter. This should display the version of Python installed.
   - Type `pip --version` to verify that `pip`, the Python package installer, is also ins Install Necessary Packages and Tools for Python

1. Update `pip`:
   - Open Command Prompt or PowerShell.
   - Type the following command to ensure `pip` is up-to-date:
     ```bash
     python -m pip install --upgrade pip
     ```

2. Install Common Python Packages:
   - Use `pip` to install packages required for your project. For example:
     ```bash
     pip install numpy pandas matplotlib
     ```

3. Set Up a Virtual Environment (Optional but Recommended):
   - Navigate to your project directory:
     ```bash
     cd path/to/your/project
     ```
   - Create a virtual environment:
     ```bash
     python -m venv venv
     ```
   - Activate the virtual environment:
     - On Windows:
       ```bash
       venv\Scripts\activate
       ```
   - Once activated, you can install project-specific packages without affecting the global Python environment:
     ```bash
     pip install package_name
     ```



# Setting up Python in VS Code

In this tutorial, we'll learn how to install and set up Visual Studio Code (VS Code) to work with Python.

---

## Features of VS Code

- **IntelliSense**: Provides code completions, parameter information, quick info, and member lists for Python programming.
- **Debugging**: Built-in Python debugging features, such as breakpoints, call stacks, and an interactive console.
- **Git Integration**: In-built Git version control allows you to manage your code with Git commands directly in the editor.
- **Extensions**: Access a vast library of extensions available in the VS Code marketplace to enhance your coding experience.

---

## Install VS Code

1. Visit [https://code.visualstudio.com](https://code.visualstudio.com) and download VS Code for your operating system (Windows, macOS, or Linux).

<img width="919" alt="vc1" src="https://github.com/user-attachments/assets/e6decfee-b293-4f8e-bb77-f1a0a73b9ffb">

2. Follow the installation process according to your system.
   
<img width="917" alt="vc2" src="https://github.com/user-attachments/assets/3188cacc-ee89-4edb-87b6-c2ff3f713727">

3. Also, ensure that it is added to the system’s **PATH** environment variable.

<img width="919" alt="vc3" src="https://github.com/user-attachments/assets/92eac16a-17a3-4254-bd85-fb8691fe0569">

4. After installation, open VS Code. You will need to install the Python extension next.

---

You are ready to launch VS Code from the start menu or the desktop shortcut if you have created it. 

It opens to the Getting Started page. Play around with the Appearance and Layout settings according to your liking.

<img width="920" alt="vc4" src="https://github.com/user-attachments/assets/c23e2674-af94-46b6-b6f7-4fba7c168401">

---

## Python Extension for VS Code

1. To install the Python extension, click on the Extensions view icon on the sidebar or use the shortcut `Ctrl+Shift+X`.
2. In the search bar, type "Python" and select the official extension from Microsoft. Then, click **Install**.

<img width="920" alt="vc5" src="https://github.com/user-attachments/assets/8a2c7de6-aeea-4ea8-8a3f-e01b82de956d">
   
3. Once installed, you will see the Python extension activated in the bottom left corner.


---

Next up, you need to inform VS Code about the Python interpreter you want it to use while providing highlighting, auto code completion, and debugging support.

Press **ctrl+shift+P** to open the **Command Palette**. Type **Python: Select Interpreter** in the search box. 

<img width="917" alt="vc6" src="https://github.com/user-attachments/assets/ae31e23e-c9a1-4294-82b3-4665c3fb6568">

A list of available Python interpreter installations displays. 

You may have more than one version of Python on your system or none at all. So, you’ll need to install Python before continuing. 

<img width="920" alt="vc7" src="https://github.com/user-attachments/assets/9a5cdce4-f31d-4cde-8980-ece55838741b">

## Create a Python Program in VS Code

Now that VS Code and Python are set up, let's create a simple "Hello, World!" program.

1. Open VS Code and create a new file named `hello.py`.
2. Write the following code in the file:

```python
print("Hello, World!")
```
<img width="920" alt="vc8" src="https://github.com/user-attachments/assets/bf435ddb-0c9c-45c1-8c50-fa0f8688c299"

3. Open the terminal in VS Code by selecting **View > Terminal** or using the shortcut `Ctrl+``.
4. In the terminal, run the program using the command:

```bash
python hello.py
```
<img width="921" alt="vc9" src="https://github.com/user-attachments/assets/d9f71295-73e4-4970-81d3-a1c238846c1c">

---

## Python Debugging in VS Code

1. To debug your code, click on the **Run and Debug** icon on the sidebar or press `F5`.
2. A dropdown will appear. Select **Python File**.
3. You can set breakpoints by clicking on the left side of the code editor. Then, when you run the debugger, the program will pause at your breakpoints, allowing you to inspect variables and step through the code.

---

## SQLite Extension for VS Code

1. To manage SQLite databases directly from VS Code, install the SQLite extension from the Extensions view.
2. Search for "SQLite" in the Extensions marketplace and click **Install**.

<img width="920" alt="vc10" src="https://github.com/user-attachments/assets/78f1bf97-0f7a-4d25-81cf-f749045df6bd">

3. Once installed, the SQLite extension will allow you to create and manage databases directly within VS Code.

<img width="920" alt="vc11" src="https://github.com/user-attachments/assets/8aa97d1c-8acc-4931-b093-e71082851427">

---

You are now ready to develop Python applications, debug them, and even manage databases, all within the VS Code environment. Happy coding!

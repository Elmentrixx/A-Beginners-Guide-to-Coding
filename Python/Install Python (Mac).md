# Installing Python (Optional for Mac Users)

By default, Apple macOS comes with Python 2 installed. However, it’s recommended to install Python 3 to follow the lessons in this course. You can check if Python 3 is installed by opening the Terminal and typing the following command:

```
python3 --version
```

This will display the installed Python version.

<img width="573" alt="mc2" src="https://github.com/user-attachments/assets/3e2934a0-d9b6-4409-89b6-1ea706e57e12">
---

### Step 1: Install Homebrew

Before installing Python 3, you may need some additional dependencies. The easiest way to handle dependencies is to use **Homebrew**, a package manager for macOS. If you don’t already have Homebrew installed, you can install it by running this command in your Terminal:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

<img width="625" alt="mac 1" src="https://github.com/user-attachments/assets/0c90ffda-d324-4d49-a2c0-11ea3e01bc8a">


---

### Step 2: Install Python 3

Once Homebrew is installed, you can install Python 3 by typing:

```
brew install python
```

---

### Step 3: Verify Python Installation

After the installation is complete, verify that Python 3 has been installed correctly by running the command:

```
python3 --version
```
<img width="739" alt="mc3" src="https://github.com/user-attachments/assets/54030923-20e1-4f09-993d-12794999e00d">
---

### Step 4: Fix Python Paths (If Needed)

Sometimes, you may face issues with the default Python version conflicting with the newly installed Python 3. To fix this, update your system's PATH so that the system prioritizes the new Python installation. You can do this by adding Python’s location to your `.bashrc` or `.zshrc` file (depending on which shell you use).

First, find out where Python was installed:

```
brew info python
```

This will return a location like `/opt/homebrew/opt/python@3.x/`.

Next, open your shell configuration file and add this line:

- For **Zsh** (default on macOS Catalina and later):
  ```
  vim ~/.zshrc
  ```

- For **Bash** (older versions of macOS):
  ```
  vim ~/.bashrc
  ```

Add the following line to the file:

```
export PATH="/opt/homebrew/opt/python@3.x/bin:$PATH"
```

Save the file and then run:

```
source ~/.zshrc   (or ~/.bashrc)
```

Finally, verify that Python 3 is correctly installed by typing:

```
python3 --version
```


---

### Step 5: Installing Xcode Command Line Tools (Optional)

If you encounter any issues during the installation of Homebrew or Python, it might be because Xcode’s command-line tools are not installed. To install them, run the following command:

```
xcode-select --install
```

This will open a pop-up window asking you to install the tools. Click "Install" and follow the instructions.

---

Once these steps are complete, you’ll have Python 3 installed on your Mac, ready for development!

# **ELE204H23**

Reguleringsteknikk

## **The tools used**

This directory uses mostly [Python](https://www.python.org/) and [Markdown](https://en.wikipedia.org/wiki/Markdown) running in [Jupyter](https://jupyter.org/) files. These files are edited and ran in [JUNO](https://juno.sh/) for iPad, or [VSCode](https://code.visualstudio.com/) with the [Jupyter "plugin"](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) for PC.

### **The CLI**

VSCode can use an integrated frame of your preffered [CLI (Command-Line Interface)](https://en.wikipedia.org/wiki/Command-line_interface). This in general just means you have a window in you VSCode window, where there is a "Terminal" or "Command-line".
Similar to how working in folders graphically requires you to be in the correct folder, this too needs you to navigate to the path where the correct folder or "workspace" is located.

The path to this directory, or the "Workspace", is depending on where you store it.

The path for me is:  
`D:\GIT_Repositories\ELE204H23\`  
but your path may differ somewhat depending on where you decided to place you workspace.

From this on, any time you read the word **'run the command `"the-command-to-run"`'**, it means:

1. open the [CLI](https://en.wikipedia.org/wiki/Command-line_interface)
2. Verify you are in the correct workspace
3. Type the `"command"`
4. Press the `Enter` button

### **Python**

---

this directory uses Python, with different add-ons called "modules".

#### **Installing modules**

For installing a module run the command `python -m pip install "name of module"`

The general syntax of installing Venv is:

```Bash
"path/to/Python/interpeter/of/your/choice/python.exe" -m pip install "module-name"
```

#### **Pip**

---

The former command may not have worked properly, and/or you may have noted the word pip in there somewhere.

[PIP (Package Installer for Python)](https://pypi.org/project/pip/) is the package manager for python.

If an error responds something similar to `pip not recognised` or `pip not found` you may need to install pip on your own.

For installing pip:

1. run the command `curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`
2. run the command `python get-pip.py`

The general syntax of installing pip is first:

```Bash
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```

to download the `get-pip.py` file that you need to run, and then:

```Bash
"path/to/Python/interpeter/of/your/choice/python.exe" get-pip.py
```

Though it should be noted that if you installed python on its own, you will most likely have gotten pip installed in the process.

#### **Venv**

---

When I work on this working directory i am using Venv to keep my tings a bit more tidy. Venv is a tool for setting up ["Virtual environments"](https://en.wikipedia.org/wiki/Virtual_environment)

##### **Installing Venv**

For installing Venv run the command `python -m pip install venv`

The general syntax of installing Venv is:

```Bash
"path/to/Python/interpeter/of/your/choice/python.exe" -m pip install venv
```

##### **Using Venv**

---

###### **Setting up A Virtual environment**

To set up the venv for this workspace, run the command `python -m venv .`.

The general syntax of setting up Venv is:

```Bash
"path/to/Python/interpeter/of/your/choice/python.exe" -m venv "path to folder"
```

###### **Starting the Virtual environment**

To activate the venv, run the command `./Scripts/activate`.

This runs a .bat file that activates your venv

The general syntax for doing this is:

```Bash
"path/to/your/workspace/Scripts/activate.bat"
```

you can also omit the `.bat` extension like so:

```Bash
"path/to/your/workspace/Scripts/activate"
```

###### **Stopping the Virtual environment**

To deactivate the venv, run the command `deactivate`.

This runs a .bat file that deactivates your venv

The general syntax for doing this is:

```Bash
deactivate
```

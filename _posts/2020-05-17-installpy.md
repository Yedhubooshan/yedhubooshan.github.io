---
title: "Python For Windows"
date: 2020-05-17
tags: [python,bot]
excerpt: "Python Installation Guide"
---

# Welcome To The PYTHON Installation Guide (windows 7 & Greater)!

## Just click the link below to get the installation files for Python and Sublime text!

## [CLICK HERE](https://drive.google.com/drive/folders/1S31YqcNyo1PRvnlIyYvlJ5TsFmZzi8sK?usp=sharing)

1. Run the python-3.8.3.exe file.
2. Click on "Add Python 3.8 to PATH"
3. Click on "Customize installation"
4. Select all features and click next.
5. Select a specific directory for python (will be helpful while running in cmd).
6. Create a folder for python and install python3 in the folder!

Now, after installation you must be good to work using python!

To check, open IDLE (python 3.8) in your desktop or in python folder!

Run the example program given in the link!

## Sublime Text 3

Sublime Text Editior help in auto completion, Colorful Text, Easy save and build!

Few Shortcuts:
- ctrl + n => New file
- ctrl + s => save
- ctrl + b => Save and Build!

For py starts, sublime is a good choice! Install according to your Windows Version!

- Right click on "my computer" icon
- Click on "Properties"
- System Type: 32bit or 64bit (filename with "3211" for 32bit, "3211 x64" for 64bit)

### Note: Always Save Python File As filename.py

### Sometimes python file execution my not work in Sublime Text! 

For that, Open Sublime Text

- Click on "Tools"
- In "Build System", See whether "Python" is selected! If not : Select it and Try running!

Still not working ???

- Click on "New Build System" inside "Build System"
- Clear the existing code and Paste the Below!

```json
	{
	"cmd":["G:\\py3\\python.exe", "-u", "$file"],
	 "file_regex": "^[ ]File \"(...?)\", line ([0-9]*)",
 	"selector": "source.python"
}

```
## Note:
### You should change the file directory to access the python build system! i.e., "G:\\py3\\python.exe" (\\ is essential in Build file)

- Save the file as newPython3.sublime-build
- Now, Change the Build System by selecting "newPython3"

### Now Run The Program And Enjoy Learning Python! Cheers!!!
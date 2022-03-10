---
title: Introduction
description: 'Introduction Post'
---

Introduction to the setup and resources needed.
<!--more-->
### Setup

Include steps of all necessary steps to get the software to run (for example, installations). Include the commands to run if necessary.

- All I have to do is be where I can run sqlmap. So I have to cd to the directory and then type `python3 sqlmap.py` and it runs. As a note, make sure the user has Python somewhere on their machine.

---

### Execution

How do you get the resource ready to use? Are there inputs to know? Please show a step-by-step guide (in a tutorial format) for readying the resource for your work. Include screenshots of successful execution and use of the software.

- I cannot test any actual websites at the moment due to not having created a website myself to work in as well as not had created an environment to be able to work in. Now if I wanted to test a website itself I'd type `python3 sqlmap.py -u http://example.com --dbs` to test the website.

![images](working-sqlmap.png)

DOWNLOADING PYTHON

1) Go to a python download for your specific device

- The user needs to download Python because in the SQL file the code to run it is written in Python, so the user needs to be able to run an updated version of Python to be able to run SQLMap.

2) After it downloads, specify that you want to save it on your C: drive.

- Saving it in your C: drive makes Python a programming language you can use anywhere on your machine.

3) Test a .py file to check if Python is working or not on your machine.

- Testing if Python works on your machine is smart to make sure Python is functioning properly without any bugs and to ensure when you run SQLMap after you download it, it works.

DOWNLOADING SQLMap

1) Go to sqlmap.org to download the zip file

- SQLMap is an easy, downloadable software where you can download it right from the site itself. If need be, there is a GitHub link to where users can see how the code was written, how it gets managed, who manages it, and the files used to create the software.

2) Click on the zip file and create a folder in your C: drive called sqlmap

- After you click the zip file, the downloaded file will appear at the bottom of the screen. Click it and it will open your file folder. Now you need to create a new folder called `sqlmap` in your C: drive preferably or wherever you keep your files.

3) cd to sqlmap folder

- Open up the terminal of your choosing and cd to wherever you stored the newly created sqlmap folder. Open the downloaded files in the original sqlmap folder and copy everything in the folder. Now, paste it in your newly created sqlmap folder and paste the contents. So, at this point the content from the last folder and this folder should be exactly alike now that the contents are copied and pasted.

4) run `python3 sqlmap.py` and the image pasted above should be what pops up

- Now when you cd to the sqlmap folder run `python3 sqlmap.py` and an image of sqlmap should pop up prompting you options.

Now once you have sqlmap up and running you are then able to use it for your educational needs. As stated before while hopefully working in an environment you can control, you can run the command `python3 sqlmap.py -u http://example.com --dbs` and have a web page to actually enter in place of example.com to be able to fully run and see if the website you chose has any vulnerabilities or not.

---

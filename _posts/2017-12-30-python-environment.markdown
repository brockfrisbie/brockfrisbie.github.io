---
layout: post
title:  "Setting Up A Python Environment on Windows 10"
date:   2017-12-30 16:52:47 -0500
author: Brock R. Frisbie
categories: Python
permalink: /2017-12-30
comments: true
---

I have been trying to learn a little bit of Python in order to work with some large Excel files that I have.
Unfortunately I found out pretty quickly that the Python IDLE setup is not very comfortable for working with 
files in various locations.  I searched around a bit trying to find a comfortable environment for working 
with Python on Windows, but everything I could find had additional software which I didn't want to deal with.


<br>
I started reading Zed Shaw's [Learn Python The Hard Way](https://learnpythonthehardway.org) this morning to 
just try to get into doing something with the Python language, and luckily I found the perfect solution.  
<br>

I decided to try to put together a really quick recap of how I got my environment together.  
<br>
<br>

<strong>Step 1: Download Python</strong>
<br>
Navigate to the [Python release site](https://www.python.org/downloads/release/python-364/),
and look for the Windows executable installer (I installed the 64 bit version). 
<br>
<br>
![download-python](/images/2017-12-30_Download Python.jpg){:class="img-responsive"} 
<br>
<br>
I don't have any screenshots of the install right now, but make sure to check the box to add Python to your "path".
If you miss this, you'll have to go into Windows settings and add it manually, so this is just much easier.

<br>
<br>
<strong>Step 2: Launch Windows PowerShell</strong>
<br>
Once Python is installed, open the Windows PowerShell (just search within the Start menu if necessary).  If you
type `python` into the PowerShell, the prompt should change to `>>>` to indicate that you are in the interactive Python
environment.  Type `quit()` to exit and go back to the normal prompt.  Through the PowerShell, you can change directories
so that you can work on files anywhere on your computer.  

Now, start up your favorite text editor, and you're ready to get started.  Here's what my very simple Python setup looks like:
<br>
<br>
![python-environment](/images/2017-12-30_Python Environment.jpg){:class="img-responsive"}

<br>
<br>
<strong>Step 3: Write a Program</strong>
<br>
Finally, write your first program.  Make sure you navigate to the directory where the file is stored, and then you can run it by 
typing `python program_name.py`
<br>
<br>
![first-program](/images/2017-12-30_First Program.jpg){:class="img-responsive"}

***

<h1>Basic Python Keylogger</h1>

<h2>Description</h2>
This project consists of a basic python keylogger that records and stores users keystrokes in a text file that is created upon the execution of the program. Although this is a basic keylogger, it offers great insight into malicious data collection methods and provides a further understand of how hackers create and execute their programs to gather user data. I plan to expand on this project in the near future, with ideas such as sending the recorded user keystrokes to a server or an email rather than the text file. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Visual Studio Code</b>
- <b>Pynput Import</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Visual Studio Code</b> 

<h2>Program walk-through:</h2>

<p align="center">
Import keyboard from pynput so keystrokes can be recorded (Note: If pynput is not already installed, you will need to use terminal to install it): <br/>
<img src="https://i.imgur.com/reegTx9.png" height="80%" width="80%" alt="Python Keylogger Steps"/>
<br />
<br />
This piece of code is telling the computer to print the keystrokes in the IDE terminal:  <br/>
<img src="https://i.imgur.com/srev00g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
When program is successful, keystrokes are written to the keystroke.txt file, and when there is an error getting the keystroke, the computer will print, "Error getting char" This would be important for a malicious actor who would need to scan through the code looking for personal information: <br/>
<img src="https://i.imgur.com/70rfRVD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If main program is ready to start, the keylogger will be set to record to the defined "KeyPressed" function. Listener.start will start the listener which in turn starts capturing the keystrokes:  <br/>
<img src="https://i.imgur.com/HBBaq3U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

<h1>Import and Parsing a File</h1>

<h2>Description</h2>
In this lab, I'm working as a security analyst who is responsible for preparing a security log file for analysis and creating a text file with IP addresses that are allowed to access restricted information.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Python Notebook</b> 

<h2>Program walk-through:</h2>

<p align="center">
Import: <br/>
<img src="https://imgur.com/4RYor1s.png" height="80%" width="80%" alt="Parsing Steps"/>
<br />
Read:  <br/>
<img src="https://imgur.com/7yXCPc5.png" height="80%" width="80%" alt="Parsing Steps"/>
<br />
Split:The output in the previous step is one big string. In this task, I'll explore how I can split the string that contains the entire imported log file into a list of strings, one string per line. <br/>
<img src="https://imgur.com/2J5uJkg.png" height="80%" width="80%" alt="Parsing Steps"/>
<br />
Append: There is a missing entry in the log file. I’ll need to account for that by appending it to the log file. I'm given the missing entry stored in a variable named missing_entry.After the portion of the code that writes to the file, another with statement uses the .read() method to read the updated file into the text variable and then display it. <br/>
<img src="https://imgur.com/VoYSzJj.png" height="80%" width="80%" alt="Parsing Steps"/>
<img src="https://imgur.com/wEPNIHn.png" height="80%" width="80%" alt="Parsing Steps"/>
<br />
Create: The next task I'm responsible for is creating a text file. This text file should include a list of IP addresses that are allowed to access restricted information. Documenting this in a text file will
help me communicate my findings to the security team.  <br/>
<img src="https://imgur.com/EzItNBd.png" height="80%" width="80%" alt="Parsing Steps"/>
<br />
My next goal is to create a with statement in order to write the IP addresses to the text file I've created in the previous step:  <br/>
<img src="https://imgur.com/ZCCEA53.png" height="80%" width="80%" alt="Parsing Steps"/>
<br />
Final step: Add code to read the file containing IP addresses. Complete a with statement that reads the text file and stores it in a new variable called text.  <br/>
<img src="https://imgur.com/sCgIRqq.png" height="80%" width="80%" alt="Parsing Steps"/>
<img src="https://imgur.com/5oyN0Sh.png" height="80%" width="80%" alt="Parsing Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

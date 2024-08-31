<h1>Filtering with grep </h1>



<h2>Description</h2>
In this lab, I learned how to use the grep command and piping to search for files and return specific information.
<br />


<h2>Practical experience gained in this Lab</h2>

- <b>Searching for error messages in a file</b> 
- <b>Searching for files that contain a specific string</b>
- <b>Searching for information in user files</b> 



<h2>Environments Used </h2>

- <b>Qwiklabs</b> 

<h2>Lab walk-through:</h2>

 <h2>Task 1: Search for error messages in a log file</h2>
In this task, I need to navigate to the /home/analyst/logs directory and report on the error messages in the server_logs.txt file.
<p align="center"> <br />
(1) I used the command "cd logs" to navigate to the logs directory. <br/>
(2) I used the command "grep error server_logs.txt" to filter the server_logs.txt file, and return all lines containing the text string error. <br/>
<img src="https://imgur.com/hu2RJN2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
   <h2>Task 2: Find files containing specific strings</h2>
 In this task, I need to  navigate to the /home/analyst/reports/users directory and use the correct Linux commands and arguments to search for user data files that contain a specific string in their names.
<p align="center"> <br />
(3) I used the command "cd /home/analyst/reports/users" to navigate to the users directory. <br/>
(4) I used the command "ls | grep Q1" to pipe the output of the ls command to the grep command to list only the files containing the string Q1 in their names. <br/>
(5) I used the command "ls | grep access" to List the files that contain the word access in their names. <br/>
<img src="https://imgur.com/KNq3SOo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
   <h2>Task 3: Search more file contents </h2>
In this task, I need to search for information contained in user files and report on users that were added and deleted from the system.
<p align="center"> <br />
(5) I used the command "cd /home/analyst/reports/user" to display the files in the /home/analyst/reports/users directory. <br/>
(6) I used the command "grep jhill Q2_deleted_users.txt" to search the Q2_deleted_users.txt file for the username jhill. <br/>
(7) I used the command "grep "Human Resources" Q4_added_users.txt" to search the Q4_added_users.txt file to list the users who were added to the Human Resources department. <br/>
<img src="https://imgur.com/MsUj5Xu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

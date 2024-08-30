<h1>Filtering with grep </h1>



<h2>Description</h2>
In this lab, I learned how to use the grep command and piping to search for files and return specific information.
<br />


<h2>Completed Tasks in this Lab</h2>

- <b>Finding the current working directory and display its contents</b> 
- <b>Navigating to a directory and list subdirectories</b>
- <b>Displaying the contents of a file</b> 
- <b>Displaying the first 10 lines of a file</b>



<h2>Environments Used </h2>

- <b>Qwiklabs</b> 

<h2>Lab walk-through:</h2>

<p align="center">
(1) I used the command "cd logs" to navigate to the logs directory. <br/>
(2) I used the command "grep error server_logs.txt" to filter the server_logs.txt file, and return all lines containing the text string error. <br/>
<img src="https://imgur.com/hu2RJN2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
(3) I used the command "cd /home/analyst/reports/users" to navigate to the users directory. <br/>
(4) I used the command "ls | grep Q1" to pipe the output of the ls command to the grep command to list only the files containing the string Q1 in their names. <br/>
(5) I used the command "ls | grep access" to List the files that contain the word access in their names. <br/>
<img src="https://imgur.com/KNq3SOo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<br />
(5) I used the command "cd /home/analyst/reports/user" to display the files in the /home/analyst/reports/users directory. <br/>
(6) I used the command "grep jhill Q2_deleted_users.txt" to search the Q2_deleted_users.txt file for the username jhill. <br/>
(7) I used the command "grep "Human Resources" Q4_added_users.txt" to search the Q4_added_users.txt file to list the users who were added to the Human Resources department. <br/>
<img src="https://imgur.com/MsUj5Xu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

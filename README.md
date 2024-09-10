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
In this task, I navigated to the /home/analyst/logs directory and reported on the error messages in the server_logs.txt file.
 <br /> <br />
(1) First, I used the command "cd logs" to navigate to the logs directory. <br/> <br/>
(2) Finally, I used the command "grep error server_logs.txt" to filter the server_logs.txt file, and return all lines containing the text string error. <br /> <br /> <p align="center">
<img src="https://imgur.com/hu2RJN2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br /> <br />

   <h2>Task 2: Find files containing specific strings</h2>
 In this task, I navigated to the /home/analyst/reports/users directory and used the correct Linux commands and arguments to search for user data files that contain a specific string in their names.
 <br />  <br />
(1) First, I used the command "cd /home/analyst/reports/users" to navigate to the users directory. <br/> <br/>
(2) Then, I used the command "ls | grep Q1" to pipe the output of the ls command to the grep command to list only the files containing the string Q1 in their names. <br/> <br/>
(3) Finally, I used the command "ls | grep access" to list the files that contain the word access in their names. 
<br/> <br/> <p align="center">
<img src="https://imgur.com/KNq3SOo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br /> <br />

   <h2>Task 3: Search more file contents </h2>
In this task, I searched for information contained in user files and reported on users that were added and deleted from the system.
 <br /> <br/>
(1) First, I used the command "cd /home/analyst/reports/user" to display the files in the /home/analyst/reports/users directory. <br/> <br/>
(2) Then, I used the command "grep jhill Q2_deleted_users.txt" to search the Q2_deleted_users.txt file for the username jhill. <br/> <br/>
(3) Finally, I used the command "grep "Human Resources" Q4_added_users.txt" to search the Q4_added_users.txt file to list the users who were added to the Human Resources department. <br/> <br/><p align="center">
<img src="https://imgur.com/MsUj5Xu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> <br />

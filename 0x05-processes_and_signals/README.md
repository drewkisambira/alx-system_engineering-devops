1.Write a Bash script that displays its own PID.

2.Write a Bash script that displays a list of currently running processes.
Requirements:Must show all processes, for all users, including those which might not have a TTY
Display in a user-oriented format
Show process hierarchy

3.Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
Requirements:
You cannot use pgrep
The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck error here)

4.Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.
Requirements:
You cannot use ps

5.Write a Bash script that displays To infinity and beyond indefinitely.
Requirements:
In between each iteration of the loop, add a sleep 2

6.We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.
Write a Bash script that stops 4-to_infinity_and_beyond process.
Requirements:
You must use kill

7.Write a Bash script that stops 4-to_infinity_and_beyond process.

8.Write a Bash script that displays:
To infinity and beyond indefinitely
With a sleep 2 in between each iteration
I am invincible!!! when receiving a SIGTERM signal
Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.

9.Write a Bash script that kills the process 7-highlander

10.Write a Bash script that:

Creates the file /var/run/myscript.pid containing its PID
Displays To infinity and beyond indefinitely
Displays I hate the kill command when receiving a SIGTERM signal
Displays Y U no love me?! when receiving a SIGINT signal
Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal

11.Manage my process

12.Write a C program that creates 5 zombie processes.


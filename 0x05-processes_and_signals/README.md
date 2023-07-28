# 0x05. Processes and signals

## General learning Objectives :heavy_check_mark:

* What is a PID
* What is a process
* How to find a process’ PID
* How to kill a process
* What is a signal
* What are the 2 signals that cannot be ignored

## Tasks :page_with_curl:

* Task 0 - Write a Bash script that displays its own PID.

* Task 1 - Write a Bash script that displays a list of currently running processes.
    Requirements:
    - Must show all processes, for all users, including those which might not have a TTY
    - Display in a user-oriented format
    - Show process hierarchy

* Task 2 - Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
    Requirements:
    - You cannot use pgrep
    - The third line of your script must be # shellcheck disable=SC2009

* Task 3 - Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.
    Requirements:
    - You cannot use ps

* Task 4 - Write a Bash script that displays To infinity and beyond indefinitely.
    Requirements:
    - In between each iteration of the loop, add a sleep 2

* Task 5 - Write a Bash script that stops 4-to_infinity_and_beyond process.
    Requirements:
    - You must use kill

* Task 6 - Write a Bash script that stops 4-to_infinity_and_beyond process.
    Requirements:
    - You cannot use kill or killall

* Task 7 - Write a Bash script that displays:
    - To infinity and beyond indefinitely
    - With a sleep 2 in between each iteration
    - I am invincible!!! when receiving a SIGTERM signal

* Task 8 - Write a Bash script that kills the process 7-highlander.

* Task 9 - Write a Bash script that:
    - Creates the file /var/run/myscript.pid containing its PID
    - Displays To infinity and beyond indefinitely
    - Displays I hate the kill command when receiving a SIGTERM signal
    - Displays Y U no love me?! when receiving a SIGINT signal
    - Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal
* Task 10 - Write a manage_my_process Bash script that:
    - Indefinitely writes I am alive! to the file /tmp/my_process
    - In between every I am alive! message, the program should pause for 2 seconds
Write Bash (init) script 101-manage_my_process that manages manage_my_process.

* Task 11 - Write a C program that creates 5 zombie processes.


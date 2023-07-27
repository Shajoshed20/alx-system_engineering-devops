# 0x04. Loops, conditions and parsing

## General Learning Objectives :page_with_curl:

* How to create SSH keys
* What is the advantage of using #!/usr/bin/env bash over #!/bin/bash
* How to use while, until and for loops
* How to use if, else, elif and case condition statements
* How to use the cut command
* What are files and other comparison operators, and how to use them

## Tasks :heavy_check_mark:

* Task 0 - Create a SSH RSA key pair

* Task 1 - Write a Bash script that displays Best School 10 times.
    Requirement:
    - You must use the for loop (while and until are forbidden)

* Task 2 - Write a Bash script that displays Best School 10 times.
    Requirements:
    - You must use the while loop (for and until are forbidden)

* Task 3 - Write a Bash script that displays Best School 10 times.
    Requirements:
    - You must use the until loop (for and while are forbidden)

* Task 4 - Write a Bash script that displays Best School 10 times, but for the 9th iteration, displays Best School and then Hi on a new line.
    Requirements:
    - You must use the while loop (for and until are forbidden)
    - You must use the if statement

* Task 5 - Write a Bash script that loops from 1 to 10 and:
    - displays bad luck for the 4th loop iteration
    - displays good luck for the 8th loop iteration
    - displays Best School for the other iterations

* Task 6 - Write a Bash script that displays numbers from 1 to 20 and:
    - displays 4 and then bad luck from China for the 4th loop iteration
    - displays 9 and then bad luck from Japan for the 9th loop iteration
    - displays 17 and then bad luck from Italy for the 17th loop iteration

* Task 7 - Write a Bash script that displays the time for 12 hours and 59 minutes:
    - display hours from 0 to 12
    - display minutes from 1 to 59

* Task 8 - Write a Bash script that displays:
    - The content of the current directory
    - In a list format
    - Where only the part of the name after the first dash is displayed 

* Task 9 - Write a Bash script that displays numbers from 1 to 100.
    Requirements:
    - Displays FizzBuzz when the number is a multiple of 3 and 5
    - Displays Fizz when the number is multiple of 3
    - Displays Buzz when the number is a multiple of 5
    - Otherwise, displays the number
    - In a list format

* Task 10 - help: read
    Write a Bash script that displays the content of the file /etc/passwd.
    Your script should only display:
    - username
    - user id
    - Home directory path for the user

* Task 11 - Write a Bash script that displays the content of the file /etc/passwd, using the while loop + IFS.

* Task 12 - Write a Bash script that displays the visitor IP along with the HTTP status code from the Apache log file.

* Task 13 - Now that you’ve parsed the Apache log file, let’s sort the data so you can get a better idea of what is going on.
    Using what you did in the previous exercise, write a Bash script that groups visitors by IP and HTTP status code, and displays this data.

# 0x0C. Web server

## General Learning Objectives

* What is the main role of a web server
* What is a child process
* Why web servers usually have a parent process and child processes
* What are the main HTTP requests

### DNS
* What DNS stands for
* What is DNS main role

### DNS Record Types
`A`
`CNAME`
`TXT`
`MX`

## Tasks

* Task 0 - Write a Bash script that transfers a file from our client to a server:
    Requirements:
    - Accepts 4 parameters
    - The path to the file to be transferred
    - The IP of the server we want to transfer the file to
    - The username scp connects with
    - The path to the SSH private key that scp uses
    - Display Usage: 0-transfer_file PATH_TO_FILE IP USERNAME PATH_TO_SSH_KEY if less than 3 parameters passed
    - scp must transfer the file to the user home directory ~/
    - Strict host key checking must be disabled when using scp

* Task 2 - Provide the domain name in your answer file.
    Requirement:
    - provide the domain name only (example: foobar.tech), no subdomain (example: www.foobar.tech)
    - configure your DNS records with an A entry so that your root domain points to your web-01 IP address Warning: the propagation of your records can take time (~1-2 hours)
    - go to your profile and enter your domain in the Project website url field

* Task 3 - Configure your Nginx server so that /redirect_me is redirecting to another page.
    Requirements:
    - The redirection must be a “301 Moved Permanently”
    - You answer file should be a Bash script containing commands to automatically configure a Ubuntu machine to respect above requirements
    - Using what you did with 1-install_nginx_web_server, write 3-redirection so that it configures a brand new Ubuntu machine to the requirements asked in this task

* Task 4 - Configure your Nginx server to have a custom 404 page that contains the string Ceci n'est pas une page.
    Requirements:
    - The page must return an HTTP 404 error code
    - The page must contain the string Ceci n'est pas une page
    - Using what you did with 3-redirection, write 4-not_found_page_404 so that it configures a brand new Ubuntu machine to the requirements asked in this task


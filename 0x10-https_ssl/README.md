# 0x10. HTTPS SSL

## General Learning Objectives

* What is HTTPS SSL 2 main roles
* What is the purpose encrypting traffic
* What SSL termination means

## Tasks

* Task 0 - Configure your domain zone so that the subdomain www points to your load-balancer IP (lb-01). Let’s also add other subdomains to make our life easier, and write a Bash script that will display information about subdomains.

* Task 1 - “Terminating SSL on HAproxy” means that HAproxy is configured to handle encrypted traffic, unencrypt it and pass it on to its destination.
    Create a certificate using certbot and configure HAproxy to accept encrypted traffic for your subdomain www..

* Task 0 - 

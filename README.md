## IIEC_RISE-FIRST-DOCKER-PROJECT
## INTRODUCTION:
## RISE-ID: RISE 2020.2.21.1
## What is Docker?
Docker is one of the revolutionary technologies based on the containerization technology created by Solomon Hykes officially released on 7th March 2013. It is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and deploy it as one package. By doing so, thanks to the container, the developer can rest assured that the application will run on any other Linux machine regardless of any customized settings that machine might have that could differ from the machine used for writing and testing the code. Docker is designed to benefit both developers and system administrators, making it a part of many DevOps (developers + operations) toolchains. For developers, it means that they can focus on writing code without worrying about the system that it will ultimately be running on. It also allows them to get a head start by using one of thousands of programs already designed to run in a Docker container as a part of their application. For operations staff, Docker gives flexibility and potentially reduces the number of systems needed because of its small footprint and lower overhead.

## What I have learned & How I will use this technology for my future projects?
I learned so many core concepts of Docker and what it can do. One of the most overwhelming feature of Docker is “Docker-compose” which uses “Infrastructure As a Code” to set up any development environments like Joomla, Drupal, Nextcloud etc.

I will use this technology for my web development. Earlier, for WordPress deployment to make websites I have to purchase hosting from different hosting websites and it costs a lot. Now, I will use “Docker-compose” to deploy WordPress in my very own system and host my websites on my local machine without paying any cost to other hosting vendors.

## PROJECT DESCRIPTION:
This is the first Docker project made with Docker Compose based on Red hat Linux-8 operating system as host. My project uses “Infrastructure as a Code” i.e. “Docker Compose” to launch a full working Joomla setup and full docker installation in one go.

## About Port No.- 8081
Port 8081 is commonly used as proxy and caching port. It is also above the service port range. Port 8081 also can run a Web server as a non root user. Other assignments for port 8081 include Apache Tomcat, an M2M Logger and a Web GUI. If port 8081 is used in a Web address, it requires a default port override to be able to connect to port 8081 in place of the typical port 80.

## COMMANDS TO RUN THE PROJECT:
To go to the workspace: Run “cd /myjoomplacompose/”
To launch the setup: Run “docker-compose up”
To terminate or stop the setup: Run”docker-compose stop”
To access the .YAML file: Go to “cd/myjoomlacompose/” then run “vim docker-compose.yml”

## What is Joomla?
https://www.joomla.org/

https://www.joomla.org/about-joomla.html
Joomla is a free and open-source content management system (CMS) for publishing web content. It is built on a model–view–controller web application framework that can be used independently of the CMS. Joomla is written in PHP, uses object-oriented programming (OOP) techniques and software design patterns, stores data in a MySQL, MS SQL, or PostgreSQL database, and includes features such as page caching, RSS feeds, printable versions of pages, news flashes, blogs, search, and support for language internationalization. Joomla is written in PHP, uses object-oriented programming techniques (since version 1.5) and software design patterns, stores data in a MySQL, MS SQL (since version 2.5), or PostgreSQL (since version 3.0) database, and includes features such as page caching, RSS feeds, printable versions of pages, news flashes, blogs, search, and support for language internationalization. Over 8,000 free and commercial extensions are available from the official Joomla Extensions Directory, and more are available from other sources. As of 2019, it was estimated to be the fourth most used content management system on the Internet, after WordPress and Drupal.

## To access Joomla Documentation:
GO TO https://docs.joomla.org/Main_Page

## Docker project to ease the use of docker:
By using this program one can easily install docker and use it as normal operating system here is complete guide to make comfortable with you with the following project. One can launch a complete WordPress server with MySQL database within one single click.

## Requirements to run the project:
You should be in Redhat linux
You should have python3 installed in your rhel
Yum should be configured
How to run:
First you have to download all three files in one single folder
Then run dockerproject.py file using python3
Eg:
python3 dockerProject.py
Then you can use this for further options available in it.

## How to use:
First you have to download all the three file in one single folder in your redhat.
2.Then follow the below instructions according to your use:
## Menu of this project is something like this:
press 1: for docker installation                                          
press 2: for docker yum error                                             
press 3: for docker-compose installation                                  
press 4: for launch wordpress site with MySQL database     
press 5  for stop the wordpress container                
press 6: for see docker                                                
press 7: for see containers running

So For installation of docker you have to press 1 on your redhat. Sometimes while we inside the docker container using yum install command it might not works it gives an error so to resolve that error use second command. This problem is basically due to the firewall. But foe this your yum should be configured.

Press 3 for docker-compose installation id you wants to run wordpress web server with integration of mysql then first you have to install docker-compose.

Press 4 for wordpress server with mysql database server within one single click and can be managed very easily. Press 5 if you wants to stop your wordress server.

Press 6 to see docker images.

Press 7 to see docker containers running at present.

## Some important about basic setup:
By default:
> Database User name : redhat
> Database root password : rootpass
> Databse password : redhat
> Database name : mydb

## Official link for reference
Here are some official links for your reference about docker:

  http:// https://www.docker.com/

## Contact details:
In case of any query regarding project :

## LinkedIn:
https://www.linkedin.com/in/yashank-mittal-613346179

 ## Email : yaashankmittal@gmail.com
## WORDPRESS LINK:
http://192.168.43.8:8081/2020/05/02/iiec_rise-first-docker-project/
Thank you

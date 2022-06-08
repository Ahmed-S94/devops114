# Steps to reload and reacreat VM 

- 'Vagrant up'

- Vagrant ssh - to go inside local machine

- sudo apt-get update - connects to the internet to recieve any updates since its latest build. If there no internet it will fail

- sudo apt-get upgrade - its looking for addition updates.

- sudo apt-get install nginx -y - nginx is a package that allows you to test internet inside the vm

- systemctl status nginx - updates on the status

- Control c to get shell back - brings you back to shell

- Exit - to leave virtual machine




#Documentation

What is DevOps?

Devops is a combination of two departments; Development and operations. The overall workflow emphasises the communication between both the IT professionals managing the environment and the software developers. Automation is essential as a DevOps engineer however fundamentally Devops involves combining development and operations into a singular continuous process.





What are the Benefits of Devops?

	-Improved Communication: When different teams or departments work on a project, communication is key to its success. But people often get caught up in their day-to-day tasks and communications start to slip through the cracks. By using DevOps and cloud computing, teams can keep everyone in the loop and things get done quicker.

	- Scalability: Organizations can more easily scale their operations by Devops. This is because software testers and developers can quickly add or remove resources as needed in order to respond to changes in demand.

	- Better Quality Control: When a business is working with multiple teams and departments, quality control can be an issue. The best way to make sure that everything is done correctly and meets the standards of the business is to implement DevOps processes and cloud computing solutions into your development efforts. This helps ensure higher-quality products and fewer errors.

	-Reduced Costs: One of the biggest benefits of using DevOps is that it can help businesses save money. This means that businesses will spend less on rework and corrections. In addition, cloud computing can help businesses stay within budget by allowing them to pay only for the resources they need.



What are the roles of a devops?

A Devops engineer role can vary on a number of factors however these are the main aspects the role entails;

 	-Testing: Tests code, processes, and deployments to identify ways to streamline and minimize errors.

	-Deployment: Uses configuration management software to automatically deploy updates and fixes into the production environment.

	-Development: Develops, codes, builds, installs, configures, and maintains IT solutions.


https://user-images.githubusercontent.com/105853978/171037852-17180782-4a7d-4267-b82f-591bdfc60d3e.png












LINUX COMMANDS

Command	Description	
ls	Lists all files and directories 
ls -R	Lists files in sub-directories as well
rm remove files
cd or cd ~	Navigate to HOME directory
cd ..	Move one level up
cd	To change to a particular directory
cd /	Move to the root directory
sudo allows admin level
mk dir makes new folder
pwd reminds me where i am 
mv 

###Bash scripting
- create a file called provision.sh
- change permission of this file called 'chmod+x provision.sh'
- first line 'MUST BE' starting with '#!/bin/bash'
- update and upgrade 
- install nginx
- 'enable nginx'
- stopped then started 
- sudo systemctl status nginx / checks status of nginx
- config.vm.synced_folder ".", "/home/????????"
- 
### WHAT IS CLOUD COMPUTING?
Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider like Amazon Web Services (AWS).

### What are the benefits and why we would use them?
There are many benefits of cloud computing here are a few;
- Reduced IT costs
- Scalability
- Flexibility
- Availability 



### Monolithic architechture 
Monolithic architecture is designed to be self-contained, wherein the program's components or functions are tightly coupled. In a monolithic architecture, each component and its associated components must all be present for code to be executed or compiled and for the software to run. 
￼
https://miro.medium.com/max/714/1*F6y9GeBZwaOzNYnToahfQw.png

###Capex vs opex 

Capital expenditure is the amount of capital that will be at expense at the start or beginning of the business.

Operational expenditure is the amount of expenditure that is lost during the running of the business. (Any expense during operation of the business.


### Explaining an AWS architecture
One the smallest scale you have the data centres which is where the data is physically stored.
A collection of data centres are referred to as an availability zone and a combination of availability zones is referred to as a region. 

When decided how many Az’s you’d like in which regions the two main factors are ’Scalability and Availability’.
￼
https://cloudacademy.com/wp-content/uploads/2017/07/Screen-Shot-2017-07-05-at-13.13.38.png


### explanation on the AWS Features


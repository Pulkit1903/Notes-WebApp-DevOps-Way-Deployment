# DevOps-01
# STEPS TO FOLLOW
1.	CREATE AN EC2 INSTANCE ON AWS WITH KEY PAIR.
2.	CHANGE THE PERMISSION OF KEYPAIR (https://youtu.be/6phF7bxY2Eo)
3.	CONNECT USING THE EXAMPLE LINK GIVEN
4.	CLONE THE REPO INTO THE SERVER.
5.	INSTALL DOCKER and give permission (**sudo usermod -aG docker $USER**)
6.	Using Docker file build a docker image (**docker build -t notes-app .**)
7.	Install java for Jenkins (**sudo apt install openjdk-17-jre**)
8.	Install Jenkins and login (**sudo cat <initial…>**) Jenkins by EDITING INBOUND RULES IN EC2 INSTANCE and ADDING 8080 with MY IP.
9.	Create a pipeline and tick on GITHUB PROJECT and provide the URL of repository.
10.	Write a descriptive Jenkins file.
11.	Add Jenkins into docker (**sudo usermod -aG docker jenkins**) and reboot the system.
12.	Login into Docker Hub. Create an environment variable for credentials in Jenkins DASHBOARD->CREDENTIALS->SYSTEM->CREATE
13.	Now tick on ID and enter the username and password of Docker Hub.
14.	Update the Jenkins file and using env variable provide the username and password. 
15.	Update the Jenkins file and start the build.
16.	After the build is completed the application is deployed in a containerized form.
17.	# Jenkins Build Image
![Screenshot 2024-01-11 123257](https://github.com/Pulkit1903/DevOps-01/assets/97504521/8374803c-a598-403d-a841-d30686289113)

# Application ScreenShot
![Screenshot 2024-01-11 123420](https://github.com/Pulkit1903/DevOps-01/assets/97504521/7ab9e629-9834-4137-8bc4-e772041f6449)


3

Get last 10 lines of logs for container jboss-eap-app
Stop the container boss-eap-app
Remove the container jboss-eap-app


4

Add a tag "6.4.v1" to the image jboss-eap (Build in Test 1)
Save the image with new tag to tar file jbos-eap.6.4.v1.tar
Push the image with new tag "6.4.v1 to docker registry


5
Run myg| container using Podman and image registry.access.redhat.com/rhscl/mysql-57-rhel7
Name of the container mydb
Expose container port 3306 to port 30306 on local h
Pass the container parameter values
MYSQL_ROOT_PASSWORD=password
MYSQL USER=user1
MYSQL_PASSWORD=password
MYSQL_DATABASE=books

6

Create an mysql application as instructed below
Name of the app is mysql-app
Use image registry.access.redhat.com/rhscl/mysq|-57-rhel7
Parameters to be used MYSQL_USER-user
MYSQL_PASSWORD=password
MYSQL_DATABASE=books
All resources should have label "aap=mydbapp"

7

Expose the service to url "mysaltestapptesturl.com"
Copy file mytestfile. txt from host to the mysql application path /tmp/
Check pod logs
Login into application and check the version of mysq|

8

Create mysql application as instructed below
Use mysql.son or mysql.yaml for application creation
Variable to be set
MYSQL_USER=user1
MYSQL_PASSWORD=password
MYSQL_DATABASE=books

9

Create Template from mysql. json or mysql. yaml file
Create mysql application as instructed below
	• ﻿Use the template created
	• ﻿Variable to be set
MYSQL_USER-user1
MYSQL_PASSWORD=password
MYSQL_DATABASE=books
![image](https://github.com/haiduc2005/DO180-apps/assets/20736187/75a08470-459f-46ee-a19a-7e6bef97f22f)
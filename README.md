# documentManagement

This document contains the instructions to deploy & start  the project.


Softwares/Installations required:
1) Download mongodb from "https://www.mongodb.com/download-center#community"

2) Follow the instructions for installing mongodb.

3) Download java(JRE) from " "http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html"
4) Follow the instruction to install java on the system. 
5) Download Tomcat from "https://tomcat.apache.org/download-70.cgi" based on the Operating System of the machine.

6) Follow the instruction to install Tomcat on the system.

Directory creation on the local machine: 
1) Create a folder "mongodb/data" in any of the drive.

For example : "D"/mongodb/data".

Start the server(DB and Application servers)

To start Mongo DB server:

    
a) Goto the folder/directory path where mongodb is installed e.g. "D:\Mongo\MongoDB\Server\3.2\bin" and type below command.
    
b) mongod --dbpath "D:/mongodb/data"


To start Tomcat Server: 
1) Go to the path where tomcat is installed : "C:\Program Files\apache-tomcat-7.0.70\apache-tomcat-7.0.70\bin"
2) Typ tomcat7.exe start to start the server.

To start the welcome page:
1) Type url "localhost:8080/MaProDMS/cmslogin".

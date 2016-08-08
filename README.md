# documentManagement


Copyright (c) 2016 Priyanka Mudgal

This Project is document Management System which gives the facility to upload/store/download the documents.

This code is available under the "MIT License". Please see the file LICENSE in this distribution for license terms.
This document contains the instructions to deploy & start  the project.



PROJECT DESCRIPTION: This project is a document Management System where the users are able to login with their login credentials, can upload the documents and once they are uploaded, the documents are stored in the repository. Later the user can see the complete list of documents they have uploaded and they have the facility to download the documents on their local systems.

Author: Priyanka Mudgal

PROJECT NAME: Document Management System

CONTACT INFORMATION: pmudgal@pdx.edu

License Information: Please check the below link to get the file license in this distribution. Link:https://github.com/prmudgal/documentManagement/blob/opensource/LICENSE

Source Code: The source code can be found at the following repository Link for repository: https://github.com/prmudgal/documentManagement/tree/opensource/MaProDMS

BUILD INSTRUCTIONS:

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



Future Enhancements:
1) To make Vaidations in place (user login).
2) Make UI a bit fancy to use.


FINAL PRESENTATION: Working on it.

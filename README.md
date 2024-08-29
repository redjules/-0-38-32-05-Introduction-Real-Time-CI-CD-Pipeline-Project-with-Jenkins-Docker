# Real-Time-CI-CD-Pipeline-Project-with-Jenkins-Docker

# Architecture
<img width="959" alt="Screenshot 2024-08-29 at 19 38 15" src="https://github.com/user-attachments/assets/a45ee6fe-7b4d-4449-97f1-4df16ede3e8e">


In this project, I build and deploy a basic Java app that will be using a back-end, front-end and database.

First I will keep the source code in GitHub, then using Jenkins I will compile the app and run 2 security tools: SonarQube and Dependency-check. SonarQube to perform a quality check and make sure there are no bugs in the source code and tehn a whole source code scan using Dependency-check to find out any known vulnerabilites in the source code. Tehen I will build the app using Maven and then create a Docker image using a Docker file and will scan the Dcoker image using trivy.  Once everything is ok, I will deploy the app inside Docker container.

This is a view of the application:

<img width="832" alt="Screenshot 2024-08-29 at 19 37 31" src="https://github.com/user-attachments/assets/51376402-64eb-4319-926b-31b1bda613dd">

<img width="835" alt="Screenshot 2024-08-29 at 19 40 10" src="https://github.com/user-attachments/assets/3a3797f5-0d8c-4a83-925b-fd889967abdf">


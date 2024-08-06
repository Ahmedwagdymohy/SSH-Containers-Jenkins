# Setup-SSH-For-Containers-Jenkins
 ## Abstract and Architecture:
 We have two containers, one is Jenkins and the other is a slave has applications & tools. We want to connect the slave to the Jenkins container. So Jenkins can run and excute commands on the other container. We will use SSH to connect the two containers based on the Docker-compose Network.

 ![schema](https://github.com/user-attachments/assets/6386458d-e333-4057-a0df-f87f8a8fee3c)
 



## Prerequisites:
- Jenkins Image with SSH-Client installed.
- Tools Image with the tools required & SSH-Server installed.
- Docker-compose installed.


## Imagine the scene :


Pull a pre-existing Docker image from a public repository (e.g. Docker Hub) and run it on your local machine. Run the container as a non-root user (Hint- Use usermod  command to give user permission to docker). Make sure you reboot instance after giving permission to user.

![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/2c3ea9da-5dee-4e55-b1cf-c9ba9a87f31a)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/395e9a8a-fba1-4b71-9404-bdc681f47706)


Inspect the container's running processes and exposed ports using the docker inspect command.


docker inspect 39cf7420045b

![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/90cf3a88-309e-462d-b011-ac470c3a3ae1)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/ef6a94e7-7ab9-467b-9cbf-59d4c8771824)


Use the docker logs command to view the container's log output.

![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/c624fd45-aff3-4ead-b66f-e4c549c89ed4)


Use the docker stop and docker start commands to stop and start the container.


![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/eee87eba-574d-4ad3-a1af-411aa4c5b0eb)

Use the docker rm command to remove the container when you're done.

![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/c35458b8-b700-42ba-aed3-77baf1b9d06d)

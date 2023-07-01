1.. You have to install docker and jenkins in your system from your terminal using package managers

a-> Install Docker 
![dockerinstall1](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/c804361b-075a-40c0-ab68-28e96c3a9d86)
![dockerversion](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/e2c74e4b-34e0-430f-a28d-55144bde73cc)

b-> Install Jenkins
![jenkins](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/971d8e16-f02b-4f59-af8f-42b16258d163)
![java-version](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/4b794749-8461-4a2e-9eaf-515ad363f357)
![jenkinsinstall](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/d117410f-6c1c-4f29-8332-e2c6fc9de2e7)
![jenkins-version](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/e9a3773e-90d7-45c8-aaf8-f01d42fb7462)

2.. check the status of docker service in your system (make sure you completed above tasks, else docker won't be installed)
![dockerstatus](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/d93d86ed-1940-48ce-8fdf-0adeba2a78fe)
![jenkinsstatus](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/8dcbe9a7-686f-43e4-8e3f-068ca3459b8e)

3.. stop the service jenkins and post before and after screenshots
![systemctl](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/b1990291-10e5-4c5f-b002-a2f57d380ac6)

4.. Systemctl Vs Service - Systemctl is given by systemd . It basically runs the command in the deamon mode , if in any case our system gets closed once we restart the system the service will still be running in the deamon mode whereas if we run the command as a service and the system gets closed in that case after starting the system we again need to up the service.

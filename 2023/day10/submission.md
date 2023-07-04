TASK 1:

Add a text file called version01.txt inside the Devops/Git/ with “This is first feature of our application” written inside. This should be in a branch coming from master, , swithch to dev branch ( Make sure your commit message will reflect as "Added new feature").
version01.txt should reflect at local repo first followed by Remote repo for review. 
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/1b3e7189-5de8-4c76-802b-b958d51cc48d)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/d02313e7-196a-4712-953d-2095a68ccecc)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/403e3430-88d2-4e3a-a02d-65afa9e386b0)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/7a9c0d4f-736d-4763-a638-f7ce7300b72f)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/d9743c8a-2c3e-4d2c-9287-fc91344d230a)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/33857a32-5550-47b4-b68c-2453f8e225a6)


TASK 2:

Whenever any code change is required it is not advised to be done directly on master/main branch/repository , so we create a copy of the of our existing code by creating a branch and make the necessary changes in the branch and once we are satisfied with the code changes the branch can be merged post review into our main repository which is the main branch 
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/77b09511-72dc-475c-ae54-fbc94479a0de)

Here, -b will create the branch if it does not exists . If the branch already exists we can skip -b and directly switch to existing branch

![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/ed2ec6d1-734f-43fd-83ba-ac2d8ac67beb)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/424d6f82-88dd-41ad-a832-9c52a7671bed)
![image](https://github.com/seematripathi/90DaysOfDevOps/assets/33751911/4063e76a-7607-4e7e-a0a7-9511883826da)

Rebasing is basically combining a sequence of commits into new base commit.

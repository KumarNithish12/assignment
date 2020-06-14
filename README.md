Task Details ::

First Job in Jenkins: 
--> developer-work: Deploying webserver

1. Giving the Github account details
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task1.png?raw=true)

2. SCM Poll : Whenever the developer modify anything , then Jenkins automatically download the code ...
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task2.png?raw=true)

3. Deploying the webpages in docker container :: Developer is testing the webserver ...
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task3.png?raw=true)

Second Job in Jenkins:
--> web-test: Testing the website

1. Triggering the job after developer-work
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task4.png?raw=true)

2. Code for testing the webpage .. Note: This code works only for php page ...
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task5.png?raw=true)

Third Job in Jenkins:
--> Merge-block: If developer code is working fine , then this job merges dev branch to master branch ..

1. Giving the credebtails to the git, and Branch specifier should be dev/
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task6.png?raw=true)

2. triggering the job after Job2:web-test
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task7.png?raw=true)

3. In post-build step , create Git publisher and do things as shown below ..
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task8.png?raw=true)

Fourth Job in Jenkins:
--> Finally deploy the webpages for client .. For this we have to launch new Docker container ..
![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/task9.png?raw=true)

Done with the task

![Test Image](https://github.com/KumarNithish12/assignment/blob/master/images/Screenshot%20from%202020-06-13%2019-45-41.png?raw=true)

This is an implementation of creating a Jenkins CI server that pulls from git hub and is based on the Amazon Cloud, following the setup outlined on this tutorial: https://www.youtube.com/watch?v=1JSOGJQAhtE

The Jenkins Server is found here: 
ec2-52-24-124-64.us-west-2.compute.amazonaws.com:8080/


Project outline:

- Configure Ec2 linux  server on amazon cloud
- Install and configure Apache tomcat web server, Java (jre and jdk), Jenkins and Maven.
- Configure Jenkins with build tools and configure it to pull from github (using rsh keys)
- Pull Github code and xecute build with maven through Jenkins and Test. 
- Set Automation schedule and ouput line sourcing with JaCoCo


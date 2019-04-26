# Project Title
Jira-Jenkins-Hubot
Jira-Jenkins-Hubot Integration

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Docker Required


### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

### JIRA HUBOT
Place  jira-env-file at Cdrive with valid configurations
### Example  Jira-env-file attached 
Give valid configurations in ENV file

### Steps

Go to command promt
Run below command

docker run -dit --env-file jira-env-file -p 8788:8788 devopsbasservice/onbotframework:slack-jirabot-ubuntu-v1

After installing 

then go to  https://practise-hq.slack.com
Username : nayana.cv@cognizant.com
Password :  Nayana-nov24

Left Hand side bottom we can find the APPs menu ---> jirabot
type  Help  in texbox it gives the list of commands which need to interact with hubot to jira

### JENKINS HUBOT
Place  jira-env-file at C: drive with valid configurations

### Example  jenkins-env-file attached 
Give valid configurations in ENV file

### Steps

Go to command promt
Run below command

docker run -dit --env-file jenkins-env-file -p 8787:8787 devopsbasservice/onbotframework:slack-jenkinsbot-ubuntu-v1

After installing 

then go to  https://practise-hq.slack.com
Username : nayana.cv@cognizant.com
Password :  Nayana-nov24

Left Hand side bottom we can find the APPs menu ---> JenkinsBot
type  Help  in texbox it gives the list of commands which need to interact with hubot to Jenkins






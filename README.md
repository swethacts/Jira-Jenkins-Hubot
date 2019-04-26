# Project Title
Jira-Jenkins-Hubot
Jira-Jenkins-Hubot Integration

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Docker Required
Jira Working Url
Jenkins working Url
Slack URL Needed (with Credentials)


### Installing

### JIRA Installation With Docker
Basic Jira installation 
docker run --detach --publish 8009:8080  --volume "hostpath:/var/atlassian/jira"  cptactionhank/atlassian-jira:latest

Check below url for more requirements

https://hub.docker.com/u/cptactionhank

#### Jennkin Installation With Doker 
docker run  -u root  --rm  -d  -p 9090:8080 -p 50000:50000  -v jenkins-data:/var/jenkins_home  -v /var/run/docker.sock:/var/run/docker.sock jenkinsci/blueocean

### JIRA HUBOT


### Steps

Go to slack chanel Create hubots in slack chanel name as Jirabot
And save the slack_token to give in JIRA env file

Place  jira-env-file at Cdrive with valid configurations
### Example  Jira-env-file attached 
Give valid configurations in ENV file


Go to command promt
Run below command

docker run -dit --env-file jira-env-file -p 8788:8788 devopsbasservice/onbotframework:slack-jirabot-ubuntu-v1

After installing 

Go to slack chanel
Left Hand side bottom we can find the APPs menu ---> jirabot
type  Help  in texbox it gives the list of commands which need to interact with hubot to jira

### JENKINS HUBOT
Go to slack chanel Create hubots in slack chanel name as Jirabot
And save the slack_token to give in JIRA env file

Place  jira-env-file at C: drive with valid configurations

### Example  jenkins-env-file attached 
Give valid configurations in ENV file

### Steps

Go to command promt
Run below command

docker run -dit --env-file jenkins-env-file -p 8787:8787 devopsbasservice/onbotframework:slack-jenkinsbot-ubuntu-v1

After installing 

Go to slack chanel
Left Hand side bottom we can find the APPs menu ---> JenkinsBot
type  Help  in texbox it gives the list of commands which need to interact with hubot to Jenkins






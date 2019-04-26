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
# Example 
HUBOT_NAME=jirabot  #valid name 

EXPRESS_PORT=8787   

MY_POD_IP=10.120.101.126    #valid IP 

HUBOT_SLACK_TOKEN=xoxb-555685734404-585039739682-qv0tffC9rZVjO3jYGrDYSrW0   #valid slack Token 

HUBOT_JIRA_URL=http://192.168.40.202:8009 #valid JIRA URL 

HUBOT_JIRA_USER=swethareddy.baikadi #valid JIRA UserName

HUBOT_JIRA_PASSWORD=feb@2019 # #valid Password 

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




And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc


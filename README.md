# Creating a DevOps Pipeline

### Architecture Diagram

![alt text][logo]

[logo]: https://github.com/MyMirelHub/DevOpsPipeline/blob/master/lab_diagram_cicd_pipeline_canary.png "Logo Title Text 2"

### Aim 
To deploy some changes to a production server

- Github - source control repository 
- Staging server - Taking the code from github and making sure the deployment works
- CI Server(Jenkins) Will orchestrate the entire  process, taking the code from github, taking it to staging and moving it into production

https://github.com/MyMirelHub/devops-essentials-sample-app

Step 1  - Fork the project
- Each set of branches contains the changes or a set of changes you are working on.

Step 2 - Check that the  jenkins server is running in the web broser

```
your-jenkings-IP:8080
```
Within the Jenkins enviroment configure branch source. 

- Add your forked branch from linux academy
- New Pull request 

Compare changes between the new and the old feature

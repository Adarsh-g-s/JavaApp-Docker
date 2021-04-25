# JavaApp-Docker
Run a JavaApp as a docker container.

The below instructions can be followed to deploy a java app on dockerhub, provided docker is already installed on the machine. 

### Dependencies

1. Dockerfile (Containes the dependencies required for the app to run, e.g., Java 8)
2. Jar file (HelloWorld.jar)

### Running locally

1. docker build command is used to create the container image and to install dependencies indicated in the docker file. 

![image](https://user-images.githubusercontent.com/26891940/115989425-93626300-a5be-11eb-81e8-a02fef56f5a0.png)

2. Run the docker containing the java app.

![FirstDockerAppDeployed](https://user-images.githubusercontent.com/26891940/115989840-99594380-a5c0-11eb-9aa5-e37bca646299.png)

### Running from dockerhub

1. Pull the repo from dockerhub as it's available publically and run the app. The result will be printed as "Hello World" on the command prompt. 

![image](https://user-images.githubusercontent.com/26891940/115990001-4f249200-a5c1-11eb-9d3c-e23491a6899b.png)

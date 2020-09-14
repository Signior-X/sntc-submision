## Question 1

For this part, I made a change in the app.js file. A library called a morgan is used for automatic logs in Nodejs. However one can use console.log and console.error wherever required. If logs are required in a file, one can also use an express-logger.

Then run the docker image without the detach argument and one can easily see the logs

So  here is what I did:
##### Learned about Docker
1. Installled docker in my Ubuntu 18.04 https://docs.docker.com/engine/install/ubuntu/#prerequisites 
2. Then followed there tutorial given on the site https://docs.docker.com/get-started/
3. And from here i learned for how to write a Dockerfile here https://www.youtube.com/watch?v=iqqDU2crIEQ&feature=youtu.be
4. I already knew how to show logs in Nodejs, just checked for if something is needed to do with using Docker also.... Nice not needed.
5. After that I wrote the Docker file with baat-cheet and installed morgan using `npm install morgan`
6. Then I did docker build and deploy on the docker hub.


## Question 2

`Option 2` 
- As containers run _independently_ so if he does a mistake, it will not effect the whole server.... so I didn't choose option1 and instead choose option1.
- Also I tried and without sudo priveleges, it's pretty not useful to use docker container.
- Now for the execution part, I will create config filed and handlover them to him. So that he can himself setup the configuration for his app. And can update the docker accordingly.
- I found the ways here https://docs.docker.com/engine/swarm/configs/


## Question 3
For this question, I tool help from https://docs.docker.com/storage/volumes/

Here they mention that we can run the docker using the following command
```
docker run -v /development-directory:/usr/local/apache2/htdocs/
```

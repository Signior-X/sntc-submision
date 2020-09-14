## Question 1

For this part, I made a change in the app.js file. A library 


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

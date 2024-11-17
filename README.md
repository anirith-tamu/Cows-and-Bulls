# Cows-and-Bulls
All the dependencies are neatly packed into respective docker images (one for frontend and one for backend). 

Since, we need communication between the two docker containers, a dockercompose.yml file is written. 
To run the yml file we need to install a few dependencies on our system. 

Run the following commands in your ubunutu terminal:
```
$ sudo apt install docker.io
$ sudo apt install docker-compose
```
After installing these dependencies. Simply run the command:
```
$ docker-compose up
``` 

The application should start at localhost:3000. Have fun! 

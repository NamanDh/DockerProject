# Docker Project
In the file, we're basically launching 2 containers, creating their persistent volumes as well.
The first container being from Joomla's Image, which furthermore needs MySQL to store data on backend, so that would be the other container.
All the necessary environment variables have been provided with the relevant values and finally, port no. 8680 has been exposed with which 
one may connect and this is going to make contact with port no. 80, for web server, in Joomla container. 
Knowing some of the basic docker-compose cmds, one may simply try it and access via the web browser by http://localhost:8680  

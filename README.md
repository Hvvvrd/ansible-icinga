---------------------------------------------------------------------------------------------------------------------------------------------------------------------############################### REFERENCE point of this project => https://github.com/VerosK/ansible-role-icinga2  ##################################################
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

INTRO -> This project is a slight adaptation of the work established by Verosk. Thx to him for the inspiration !
Our starting point is a Icinga Monitoring Distributed with 1x Master/ 2x Satellites / somes agents.
Master and satellites are containerized via Docker in a swarm cluster. 
We modified the stack from Eric LIPPMANN (CTO @Icinga) found on his github repository : https://github.com/lippserd/docker-compose-icinga
Beyond conteneurization, our goal was to set up an automated deployment and configuration of news agents in our Icinga Monitoring Distributed.

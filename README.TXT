Docker project
This project is based on two container images which are (a)mysql:5.7 and (b)postfixadmin:latest.
For the above image you have to use "docker push kshitizlinux/postfixadmin:latest" and "docker push kshitizlinux/mysql:5.7".

Required os:-
RehHat8,docker-ce and ,docker-compose.

command "docker-compose up -d"
After running this command run http://localhost:8080/setup.php
bydefault setup password is topsecret99.



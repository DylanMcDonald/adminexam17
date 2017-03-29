# Admin Exam 2017 AGM
Total Marks: 50

## Linux [ Marks]

1.
2.
3.
4.
5.
6.
7.
8.
9.
10.

## BSD [ Marks]

1.
2.
3.
4.
5.
6.
7.
8.
9.
10.

## Networking [ Marks]

1.
2.
3.
4.
5.
6.
7.
8.
9.
10.

## File System [ Marks]

1.
2.
3.
4.
5.
6.
7.
8.
9.
10.

## Security [ Marks]

1.
2.
3.
4.
5.
6.
7.
8.
9.
10.

## Scripting [30 Marks]
This Section can be written in a language of your choice

1. Mailing lists are broken and we need to send the announce to all our users.
   Write a script to send the announce to our list of users, which is stored in
   a csv file, of `name,username,alt-mail` called `iShouldntHaveThis.csv`. (3 marks)
2. Write a script that takes usernames and password hashes from /etc/shadow.
   The script should then try and crack them using john the ripper. If the
   password is found in under 10 minutes email the user their password and tell
   them it's shit (10 marks)
3. A user has been disusered but is still spawning processes. Write a Script to
   find all processes by this user and kill them every 10 minutes. But you can
   not use pkill, pgrep or killall(10 marks)
4. Write a script to scan all users web directories for world editable files.
   Change there permissions to the correct permissions and email the user
   telling them the file you changed and why this is important (5 marks)
5. Write something to make us laugh(2 marks)

## Docker [20 Marks]

1. What is Docker? What does Redbrick use it for? (2)
2. How do you make data persist across a container restart? Give an example of
   the command. (2)
3. What are 2 methods of getting logs out of a docker container. (2)
4. You try to run a container and it doesn’t start. How would you go about debugging
   the problem? (3)
5. What Command do you use to update a docker image? (1)
6. What is the difference between docker attach and docker exec and why would
   you use one over the other? (2)
7. What Is Docker-compose? What does Redbrick use it for? (2)
8. When should you use a docker-compose file vs a Dockerfile? (3)
9. What is a container orchestrator? And why does redbrick not currently use
   one? (2)
10. Give the docker command to run a container with port 8000 on the container bound to port 80 on the host? (1)

## Practical [ Marks]

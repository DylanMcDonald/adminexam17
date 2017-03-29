# Admin Exam 2017 AGM
Total Marks: 80

## GNU/Linux [30 Marks]

1. What is systemd (2 makrs)
2. What does LVM stand for and what does that actually mean (3 marks)
3. A user has somehow renamed a file to a name with strange unicode characters
   and you cannot delete that file by name. How would you go about deleting
   that file? Give commands with parameters. (4 marks)
4. You’ve just royally screwed your shell by catting a binary. How do you fix
   this? (2 Marks)
5. You’re trying to unmount /storage, but it keeps complaining about being busy.
   How do you find out what/who is using it, and kill the process/user? Also,
   how do you unmount without killing the user/process? (4 marks)
6. You have a list of compressed files in /var/log. You need to search through the logs.
   Give 3 ways of doing this. (3 marks)
7. Give 5 advantages to getting a package from a package manager rather then building
   it yourself. What Command would you run to install and update packages on a
   redbrick server (5 marks)
8. You want to create a user to be used by a daemon. What do you set its shell
   to? (2 marks)
9. What is fail2ban? Is it a good idea to run it on your server, why? (2 marks)
10. What Is a chroot? Why might you use one? (3 marks)

## BSD the Os not the Licence [ Marks]

1.
2.
3.
4.
5.
6.
7.
8.
9.
10. Why does Redbrick have a BSD machine (2 marks)

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

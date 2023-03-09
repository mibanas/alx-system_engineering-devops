1- Create a script that switches the current user to the user betty : su betty
2- Write a script that prints the effective username of the current user : whoami
3- Write a script that prints all the groups the current user is part of : groups
4- Write a script that changes the owner of the file hello to the user betty: chown betty hello
5- Write a script that creates an empty file called hello: touch hello
Write a script that adds execute permission to the owner of the file hello : chmod u+x hello
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello : chmod gu+x,o+r hello
Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello : chmod ugo+x hello
8- chmod 007 hello
9- chmod 753 hello
10- chmod --reference=alleh hello

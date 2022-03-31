sudo su -switches the current user
whoami shows the username of the current user
chown betty hello- this script changes the owner of the file
touch hello- this creates empty file
chmod u+x gives the file execute permission
chmod ug+x,o+r gives specific permissions
chmod ugo+x gives everyone execute permissions
chmod 700 gives all other users permissions except the owner and group
753 permissions to file - read, write, execute + read execute + write execute
664 mirrors file name
Create directory and give permissions mkdir -m 751 dir_name

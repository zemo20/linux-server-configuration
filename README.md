# linux-server-configuration
a udacity server configuration tutorial project

## Server details

IP: 54.93.199.105

SSH Port : 2200

full url : http://ec2-54-93-199-105.eu-central-1.compute.amazonaws.com

## Software installed 

pip, virutalenv, apache2, mod_wsgi, sql_alchemy, mysql_server, flask, git, postgresql

## Configurations made

-Created a grader user then created an ssh key for it

-Gave grader sudo access from /etc/sudoers.d directory

-from /etc/ssh/sshd_config changed ssh port to 2200 from 22

-using ufw, allowed htpp , ntp and ssh ports

-using apt-get, updated and installed all packageds

-cloned my project https://github.com/zemo20/guitarshop

-created wsgi files in both my project and apache2 directory, with the configuration to run the server

-in psql created user psql and granted him all permissions for catalog db

-fixed a bug in pip that prevented main.py from running

## 3rd party references

https://devops.profitbricks.com/tutorials/install-and-configure-mod_wsgi-on-ubuntu-1604-1/


http://suite.opengeo.org/docs/latest/dataadmin/pgGettingStarted/firstconnect.html


https://stackoverflow.com/questions/22483555/give-all-the-permissions-to-a-user-on-a-db


https://www.liquidweb.com/kb/install-git-ubuntu-16-04-lts/


https://stackoverflow.com/questions/28210269/importerror-cannot-import-name-main-when-running-pip-version-command-in-windo


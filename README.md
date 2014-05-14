## HHVM Hack and Nginx

Install script for Ubuntu servers installing HHVM, Nginx and configures it for you.
Add myslql-server and it's made for WordPress.

#### Install 
1. copy `install.sh` to server
2. `chmod 700 install.sh`
3. run `./install.sh` with a user with `sudo` access
4. remove `install.sh` from server
5. install mysql `sudo apt-get install mysql-server`

##### Optional stuff
- [permissions file to run to fix permissions on files and directories](https://gist.github.com/chuckreynolds/11250053)
- [nginx.conf file used for wordpress sites](https://gist.github.com/chuckreynolds/939d95a9eb4f39cc44ed)

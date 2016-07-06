# GeneriTech Documentation

## Requirements
- [Vagrant](https://www.vagrantup.com/) 

## Setting up the local enviroment
1. [Download Grav](https://github.com/getgrav/grav/releases/download/) 
2. Extract everything other than the user directory into the public directory
3. Open the repository in Terminal/Command Prompt
4. Run `vagrant up`
5. Ssh into the virtual machine. IP: `127.0.0.1` Port: `2222` Username: `vagrant` Password: `vagrant`
6. Navigate to the web root `cd /var/www/public`
7. Install Grav `./bin/grav install`

## Developing

You can start the virtual machine by running ` vagrant up` and stop it with `vagrant halt`. The webserver is accessible by navigating to http://192.168.33.10/ in your browser.

The files that contain the content are located inside the `/public/user` directory. Those are the only files that should be edited, as those are the ones stored in GitHub.

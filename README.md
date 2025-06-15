#Project title 
 Shaping the future of AI powered in healthcare

## EC2 Provisioning 
 Lauch new instance
 Name the instance 
 Generate a new key pair
 download "cloudproject1-"
 SSH client 

 ### Setting up a web server
   sudo apt update
   sudo apt install nginx -y
   sudo systemctl status nginx
   sudo ufw allow
   sudo ufw allow 'nginx'
  sudo ufw allow 'Nginx Full'

#### creating a landing page on html
 http://127.0.0.1:5500/Cloudproject1-/index.html

 #### configuration
   sudo vi /etc/nginx/sites-available/myapp
     sudo ln -s /etc/nginx/sites-available/myapp /etc/nginx/sites-enabled/
     mkdir public
     mv ../index.html public
     ls public
     npm init -y
     npm install express
     node server.jscurl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
     curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
     sudo apt install -y nodejs
     npm init -y
     npm install express
     node server.js
     http://18.220.97.103/
 

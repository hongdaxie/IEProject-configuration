# These two configuration file is used to configure the host in AWS EC2 instance

# Nginx-configuration
The configuration in the server 

### upload the configuration to /etc/nginx/sites-available/age50vaccine.ml

### creating a link from it to the sites-enabled directory

sudo ln -s /etc/nginx/sites-available/age50vaccine.ml /etc/nginx/sites-enabled/

### run "sudo service nginx reload"

# Back-end service configuration

### go to "/etc/systemd/system/" folder
### create a file named "backendAPI.service" and put the content of backend service configuration file into the new created file

### run "sudo systemctl start backendAPI.service" command

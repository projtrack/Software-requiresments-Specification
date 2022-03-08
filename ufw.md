## ufw
sudo ufw allow [Service/Portnumber]
sudo ufw status numbered  
sudo ufw delete 

## Users
sudo adduser _new_username_
sudo usermod -aG user42 your_username  
sudo usermod -aG evaluating your_new_username

getent group user42  
getent group evaluating

groups

chage -l 

## Hostname 
hostnamectl 
hostnamectl set-hostname
sudo nano /etc/hosts

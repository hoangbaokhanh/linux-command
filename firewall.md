#Configuring a Basic Firewall
Install firewall: `sudo yum install firewalld`
Start firewall:  `sudo systemctl start firewalld `

##Add service to firewall by name
`sudo firewall-cmd --permanent --add-service=ssh`

##Add service to firewall by port and protocol
`sudo firewall-cmd --permanent --add-port=4444/tcp`

##Remove service by name
 `sudo firewall-cmd --permanent --remove-service=ssh`
 
 ##Some services firewall can understand
 - ssh
 - http
 - https
 - smtp
 
 For more information, can check by command `sudo firewall-cmd --get-services`
 
 ## List changed:
 `sudo firewall-cmd --permanent --list-all`
 
 ##Reload after change
 `sudo firewall-cmd --reload`
 
 ##Enable firewall (if disabled)
 `sudo systemctl enable firewalld`

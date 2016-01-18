# linux-server-configuration
This repository holds the data needed for Full Stack Web Developer Nanodegree - Linux Server Configuration exam

IP: 52.35.26.80

PORT:  2200

URL: http://52.35.26.80

SUMMARY OF INSTALLED SOFTWARE AND CONFIGURATION CHANGES MADE
I installed:
* postgresql
* git
* apache2
* libapache2-mod-swgi
* fail2ban
* openssh-server
* ufw

I added requested users, added grader to sudoers, changed ssh port as requested.
I configured ufw to accept requests only from my customized ssh port and apache.
I reconfigured tzdata.
Then I installed my application and modified it to use PostgreSQL and wsgi.
 

RESOURCES:
* https://discussions.udacity.com/t/markedly-underwhelming-and-potentially-wrong-resource-list-for-p5/8587
* https://help.ubuntu.com/community/AutomaticSecurityUpdates#Using_cron_and_aptitude
* https://mediatemple.net/community/products/dv/204643810/how-do-i-disable-ssh-login-for-the-root-user
* http://askubuntu.com/questions/59458/error-message-when-i-run-sudo-unable-to-resolve-host-none

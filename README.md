# LDAP
Ldap installation scripts 


Prerequisites:

 1. createrepo package should be installed on target machine.

 2. hostname should be configured into /etc/hosts file

 3. sudoers file shoud be modified if need to run ldap without sudo access.

 4. create local repository using createrepo and install 389 directory server with all dependency


Installation:

 1. install 389 directory server using playbook 

 2. install 389 console on windows


Configuration:

 1. Apply regex on config-template to configure ldap as per requirement
 
 2. COnfigure start and stop directory server
 
 
 
 


 

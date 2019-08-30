# LDAP
Ldap installation scripts 


Prerequisites:

 1. createrepo package should be installed on target machine.

 2. hostname should be configured into /etc/hosts file

 3. sudoers file shoud be modified if need to run ldap without sudo access.

 4. create local repository using createrepo and install 389 directory server with all dependency
 
 5. configure ansible-valut for storing ldap password
 
 6. configure inventory host file to set ldap target machine


Installation:

 1. install 389 directory server using playbook 

 2. install 389 console on windows


Configuration:

 1. Apply regex on config-template to configure ldap as per requirement
 
 2. COnfigure start and stop directory server
 
Command:

 ansible-playbook install389.yml -e "configFile=config.ini hosts=LDA" -i /etc/ansible/inventory
 
 
- /etc/ansible/inventory : this file contains Target machine with ip or hostname configure for ldap instalation it must be configure        inventory file with hostname
 
 
 
 


 

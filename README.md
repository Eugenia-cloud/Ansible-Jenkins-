# Ansible-Jenkins- 
Ansible/Jenkins integration 
https://github.com/donjevas/Ansible-Jenkins-.git 
1.	Log in to the jenkins server and start Jenkins
2.	Install ansible on the Jenkins sever
-	sudo yum-config-manager --enable epel
-	sudo yum install ansible
-	or “sudo amazon-linux-extras install ansible2”
-	https://linuxhint.com/install_configure_ansible_rhel8/
3.	go to the Jenkins GUI and install ansible plug ins
4.	go to global configuration and configure ansible, on the CLI run “which ansible” and get the ansible installation path, use the path for the configuration * copy the folder without the ansible at the end.
5.	Create new job on Jenkins GUI “ansible-test” and select pipeline
6.	Used pipeline syntax help
Pipeline{
         Agent any
         Stages{
                  Stage(‘SCM Checkout’){
                           Steps{
                                       https://github.com/donjevas/Ansible-Jenkins-.git 

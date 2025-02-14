#User & Group Management

Create a user devops_user and add them to a group devops_team
  * useradd devops_user
  * groupadd devops_team
  * gpasswd devops_user,harshitha devops_team
  
Set a password and grant sudo access
  * usermod -aG sudo devops_user
  * check user is added to sudo access or not - give "whoami" command if you can root in output that means 
    user have sudo access

Restrict SSH login for certain users in /etc/ssh/sshd_config
  * vi /etc/ssh/sshd_config 


 


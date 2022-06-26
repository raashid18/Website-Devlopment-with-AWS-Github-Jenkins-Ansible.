# Website Devlopment with AWS, Github, Jenkins & Ansible.

# Deploy 4 Amazon Linux EC2 Instance.

1. Developer Server
2. Ansible Server
3. Jenkins Server
4. Web Server

# Connect the Jenkins server through the putty.

1. Download and Install the jenkins.
2. Install the git in jenkins server.
3. Public Ip Address of jenkins server IP:8080
4. Access this IP in new tab.
5. Install recommended plugins and set username and passwd.
6. Connect the Jenkins server with Ansible server and take access of Ansible Server.
7. Install the additional plugins from jenkins.
8. Cretae a new job with freestyle project.

# Connect the Ansible server through the putty.

1. Install Ansible and required things.
2. Generate the key {ssh-keygen}.
3. Create a playbook.yml file and write the required ciommand in it.
4. Connect the Ansible server with Web server and take access of Web Server.

# Connect the Web server through the putty.

1. Install the Apache Server.
2. Start and enable the apache server.
3. Create password.

# Create a repository in the github named "Web Devlopment".

1. Now integrate Jenkins with github, copy the url of jenkins.
2. Open the setting of repo, find the webhook and create a new webhook and paste the url of jenkins & fill the required fileds in the the webhook and click OK.

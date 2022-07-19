# Website Development with AWS, Github, Jenkins & Ansible.

![Developer](https://user-images.githubusercontent.com/67089791/175803037-47bce0e0-30d7-4d9a-a414-55074d57fc03.png)


# Ansible

* Ansible is a open-source IT configuration managemement, deployment & orchestration tool. It aims to provide large productivity gains to a wide variety of Automation challages.
* Ansible Automation Platform has grown over the past years to provide powerful automation solutions that work for operators, administrators and IT decision makers across a variety of technology domains. It’s a leading enterprise automation solution from Red Hat®, a thriving open source community, and the de facto standard technology of IT automation.
* Ansible works on Push mechanism.
* We can use this tool whatever our servers are in on-premises or in the cloud.
* Ansible use YAML(Yet Another Markup Language) file to write the playbooks.

# Jenkins

* Jenkins is a self-contained, open source automation server which can be used to automate all sorts of tasks related to building, testing, and delivering or deploying software.
* Jenkins can be installed through native system packages, Docker, or even run standalone by any machine with a Java Runtime Environment (JRE) installed.

# Amazon Web Service(AWS)

* The full form of AWS is Amazon Web Services. It is a platform that offers flexible, reliable, scalable, easy-to-use and, cost-effective cloud computing solutions.
* AWS is a comprehensive, easy to use computing platform offered Amazon. The platform is developed with a combination of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings.
* Amazon Web Services offers a wide range of different business purpose global cloud-based products. The products include storage, databases, analytics, networking, mobile, development tools, enterprise applications, with a pay-as-you-go pricing model.

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

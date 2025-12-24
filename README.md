# Provisioning-Web-Servers-With-Ansible
You have a new project at your company that requires 3 new web servers. The requirements are that the web servers must be all consistent, configuration must be controlled and be quick to apply. Each web server must adhere to the given configuration parameters. All VMs will be running in AWS.

# Instructions Summary
The Ansible playbook should do the following:
* Run the playbook against the `aws` host group which contains the 3 EC2 instances
* Ports `80` and `443` open on firewalld
    * If you have re-provisioned or have not used the demos in this course, you’ll need to also include a task to install firewalld via the package module and then via the service module start firewalld. If you are using the same EC2 instances you did for exercises and demos, you will not need to install firewalld
* Item 2a
* Item 2b
    * Item 3a
    * Item 3b

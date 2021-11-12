# Installing Ansilble on various Linux OS are shown below:


### Windows

- Install virtual box and run a linux OS from osboxes.org and follow below:


### On Linux, precisely for amazon-linux2

- sudo yum update -y
- sudo yum install python-boto python-boto3
- sudo rpm -Uvh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
- sudo amazon-linux-extras install ansible2 -y 
- sudo yum install ansible -y


### For RHEL/CentOS systems

- python-pip and ansible are available via the EPEL repository.
- In order to see if EPEL repo is already available, use command--> yum repolist | grep epel
- use this command for RHEL/CentOS 6--> rpm -ivh http://d1.fedoraproject.org/pub/epel/6/x86_64/\ epel-release-6.8.noarch.rpm


### For RHEL/Centos7 

- use--> yum install epel-release


### For Debian/Ubuntu

- sudo apt-get install python-software-properties
- sudo apt-add-repository -y ppa:ansible/ansible
- sudo apt-get update
- sudo apt-get install -y ansible



# Upon successful installation, type ansible --version (to verify) if ansible if available.

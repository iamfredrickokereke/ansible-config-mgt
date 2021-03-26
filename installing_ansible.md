## On Linux, precisely for amazon-linux2

sudo yum update -y
sudo yum install -y python-boto python-boto3
sudo rpm -Uvh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
sudo amazon-linux-extras install ansible2 -y 
sudo yum install ansible -y

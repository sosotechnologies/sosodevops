# Sosotech DevOps Project

## Install Jenkins in RHEL and AWS
sudo su -

sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key

sudo amazon-linux-extras install epel

amazon-linux-extras  //version to install, java-openjdk11, version I got

amazon-linux-extras install java-openjdk11

yum install jenkins

jenkins start

chkconfig jenkins on

cat /var/lib/jenkins/secrets/initialAdminPassword

## Jenkins Ubuntu Script
Script link will be provided



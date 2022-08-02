# jenkins-setup
============= Install Java  ===========
apt install default-jre
apt install default-jdk

============= Install Maven ===========
apt install maven

============= Install Git==============
apt-get install git

============= Install Jenkins =========

wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -

sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'

apt-get update

apt install jenkins

systemctl start jenkins

systemctl status jenkins

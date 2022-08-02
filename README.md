# jenkins-setup
<br>============= Install Java  ===========</br>
<br>apt install default-jre<br>
<br>apt install default-jdk<br>

<br>============= Install Maven ===========</br>
apt install maven

<br>============= Install Git==============</br>
<br>apt-get install git<br>

<br>============= Install Jenkins =========</br>

<br>wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -</br>

<br>sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'</br>

<br>apt-get update</br>

<br>apt install jenkins</br>

<br>systemctl start jenkins</br>

<br>systemctl status jenkins</br>

============= Install Maven ===========
<br>mvn clean</br>
<br>mvn clean test</br>
<br>mvn clean package</br>
<br>mvn clean package install</br>
<br>mvn -Dmaven.test.skip=TRUE install</br>

#STEP-1: GETTING REPO   (jenkins.io)
sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key

#STEP-2: INSTALL JAVA
amazon-linux-extras install java-openjdk11 -y

#STEP-3: INSTALL GIT MAVEN JENKINS 
yum install git maven jenkins -y

#STEP-4: STARTING JENKINS SERVEICE
systemctl start jenkins.service
systemctl status jenkins.service

STEP-5: CONNECTION
publicip:8080 (browser)

yum remove java* -y

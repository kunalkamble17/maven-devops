# maven-devops
Jenkins

What is Jenkins?
Jenkins is opensource ci-cd tool used to automate the Contious Integration and Contuous Deployment Process.

What is difference between Contiuous Delivery and Continuous Deployment ?

Install Jenkins on Amazon Linux 2023
Ref Link: https://www.jenkins.io/doc/tutorials/tutorial-for-installing-jenkins-on-AWS/

# 

yum install java-11-amazon-corretto
java -version
wget -O /etc/yum.repos.d/jenkins.repo     https://pkg.jenkins.io/redhat-stable/jenkins.repo
rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
yum upgrade
yum install jenkins -y
systemctl start jenkins
systemctl enable jenkins



Testing the webhook

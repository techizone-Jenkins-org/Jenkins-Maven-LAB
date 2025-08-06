# Maven Installation
Build the Artifact by Passing Parameters to maven command

## Maven Installation
source
```
https://maven.apache.org/install.html
```
####  Installation of openJDK
## Amazon Linux
```
sudo dnf update -y
sudo yum install java-17-amazon-corretto-devel -y
``` 

####  Installation of Maven
```
sudo wget https://dlcdn.apache.org/maven/maven-3/3.9.11/binaries/apache-maven-3.9.11-bin.tar.gz
sudo tar xzf apache-maven-3.9.11-bin.tar.gz -C /opt
sudo ln -s apache-maven-3.9.11 /opt/maven
``` 
sudo vi /etc/profile.d/maven.sh
```
export M2_HOME=/opt/maven
export PATH=${M2_HOME}/bin:${PATH}
```
Reload profile
```
sudo chmod +x /etc/profile.d/maven.sh
source /etc/profile.d/maven.sh
mvn -version
```

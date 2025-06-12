# Jenkins_Build_withs_mvn_cmd_param
Build the Artifact by Passing Parameters to maven command

## Maven Installation
source
```
https://maven.apache.org/install.html
```
####  Installation of openJDK
```
yum install java-[VERSION]-openjdk-devel
sudo alternatives --install /usr/bin/java java usr/lib/jvm/java-[VERSION]-openjdk/bin/java 1000
sudo alternatives --install /usr/bin/javac javac /usr/lib/jvm/java-[VERSION]-openjdk/bin/javac 1000
/usr/sbin/alternatives --config java
``` 
HERE replace VERSIOn with java-version-number

####  Installation of MAven
```
wget https://www-eu.apache.org/dist/maven/maven-3/3.6.3/binaries/apache-maven-3.6.3-bin.tar.gz
sudo tar xzf apache-maven-3.6.3-bin.tar.gz
sudo ln -s apache-maven-3.6.3 maven
``` 
sudo vi /etc/profile.d/maven.sh
```
export M2_HOME="/opt/maven"
export PATH="${M2_HOME}/bin:${PATH}"
```
Reload profile
```
source  /etc/profile
```

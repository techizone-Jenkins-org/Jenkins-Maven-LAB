### Clone the Repo
```
git clone https://github.com/techizone-Jenkins-org/Jenkins-Maven-LAB.git
cd Jenkins-Maven-LAB/02.PassParametersRunTimeViaMVN
```

### Execute mvn command without Parameters
```
mvn clean package
```

## Passing parameters to mvn command
```
mvn clean package -Dusername="USER1" -Dpassword="pwd1"
```

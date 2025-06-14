### Clone the Repo
```
git clone https://github.com/techizone-Jenkins-org/Jenkins-Maven-LAB.git
cd Jenkins-Maven-LAB/03.Real-Time_Use-case_mvn_pass_prm/02.RunDiffTestNG_Browsers_using_parameter
```

### Execute mvn command without Parameters
```
mvn clean package
```

## Passing parameters to mvn command
```
mvn clean package -DsuiteFile="SanitySuit.xml"  -DbrowserProperty="Chrome"
```

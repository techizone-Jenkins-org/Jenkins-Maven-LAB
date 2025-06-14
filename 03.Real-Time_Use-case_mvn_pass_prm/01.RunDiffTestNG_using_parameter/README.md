### Clone the Repo
```
git clone https://github.com/techizone-Jenkins-org/Jenkins-Maven-LAB.git
cd Jenkins-Maven-LAB/03.Real-Time_Use-case_mvn_pass_prm/01.RunDiffTestNG_using_parameter
```

### Execute mvn command without Parameters
```
mvn clean package
```
HERE you notice it wil take the default values "Sanity_Suite.xml" mentioned in "pom.xml"
## Passing parameters to mvn command
```
mvn clean package -DsuiteFile="RegressionSuit.xml"
```

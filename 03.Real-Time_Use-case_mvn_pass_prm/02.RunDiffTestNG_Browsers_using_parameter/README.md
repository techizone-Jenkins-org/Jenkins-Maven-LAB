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
mvn clean package -DsuiteFile="Sanity_Suite.xml"  -DbrowserProperty="Chrome"

mvn clean package -DsuiteFile="Regression_Suite.xml" -DbrowserProperty="Firefox"

mvn clean package -DsuiteFile="Sanity_Suite.xml"  -DbrowserProperty="Edge"
```

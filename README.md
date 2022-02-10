# Basic Maven Example

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=Akashec1007_maven-basic-github)](https://sonarcloud.io/summary/new_code?id=Akashec1007_maven-basic-github)

[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=Akashec1007_maven-basic-github&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=Akashec1007_maven-basic-github)

This simple Maven project is importing JaCoCo's coverage report. For multi-module project example 
see [multi-module Maven project](../maven-multimodule/README.md)

## Usage

* Build the project, execute all the tests and analyze the project with SonarQube Scanner for Maven(from root  of the project):

```shell
        mvn clean verify sonar:sonar
```

## Documentation

[SonarScanner for Maven](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner-for-maven/)

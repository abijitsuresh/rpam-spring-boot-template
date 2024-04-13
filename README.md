# rpam-spring-boot-template
RHPAM Spring boot template application

### Projects are generated using below commands:
Model:
```
mvn archetype:generate \
  -DarchetypeGroupId=org.kie \
  -DarchetypeArtifactId=kie-model-archetype \
  -DarchetypeVersion=7.74.1.Final \
  -DgroupId=com.abijit.jbpmpoc \
  -DartifactId=my-rhpam-project-model \
  -Dversion=1.0.0-SNAPSHOT \
  -Dpackage=com.abijit.jbpmpoc.model
```
KJar:
```
mvn archetype:generate \
  -DarchetypeGroupId=org.kie \
  -DarchetypeArtifactId=kie-kjar-archetype \
  -DarchetypeVersion=7.74.1.Final \
  -DcaseProject=true \
  -DgroupId=com.abijit.jbpmpoc \
  -DartifactId=my-rhpam-project-kjar \
  -Dversion=1.0.0-SNAPSHOT \
  -Dpackage=com.abijit.jbpmpoc
```
Service:
```
mvn archetype:generate \
  -DarchetypeGroupId=org.kie \
  -DarchetypeArtifactId=kie-service-spring-boot-archetype \
  -DarchetypeVersion=7.74.1.Final \
  -DgroupId=com.abijit.jbpmpoc \
  -DartifactId=my-rhpam-project-service \
  -Dversion=1.0.0-SNAPSHOT \
  -Dpackage=com.abijit.jbpmpoc.service \
  -DappType=bpm
```

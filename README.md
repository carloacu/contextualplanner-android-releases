Contextualplanner Android releases
==================================

Maven repository for the Contextualplanner Android releases


### Command line to generate a version

```bash
mvn install:install-file -DgroupId=com.github.carloacu -DartifactId=contextualplanner-android -Dversion=1.0.2 -Dfile=contextualplanner-release.aar -Dpackaging=aar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true
```

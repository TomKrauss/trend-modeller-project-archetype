# trend-modeller-project-archetype

A maven archetype to create a TREND Modeller project. To use it:

- clone this repository.
- run `mvn install` in the directory which is created by the clone.
  
Now you may create TREND Modeller Maven Projects using a command like the following:

```
mvn archetype:generate -DarchetypeGroupId=de.gebit.trend\
   -DarchetypeArtifactId=trend-modeller-project-archetype\
   -DarchetypeVersion=1.0-SNAPSHOT -DgroupId=de.gebit.trend\
   -DartifactId=workshop -DmodelLoader=Defaultmodelloader\
   -Dpackage=de.gebit.trend.mtest\
   -Dversion=0.0.1
```

The variables `groupId`, `artifactId`, `modelLoader` and `package` may be redefined as required.


Enjoy

Tom

 

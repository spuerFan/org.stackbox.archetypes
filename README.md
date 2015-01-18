org.stackbox.archetypes
===

It's a set of maven3 archetypes during my career, with convenient usage.


###Create SSM Project


    mvn archetype:generate 
     -DarchetypeGroupId=org.stackbox.archetypes 
     -DarchetypeArtifactId=webapp-ssm-basic
     -DarchetypeVersion=0.0.2-RELEASE
     -DgroupId=<my.groupid>
     -DartifactId=<my-artifactId>

###Create MR Project for Hadoop1.x

    mvn archetype:generate 
     -DarchetypeGroupId=org.stackbox.archetypes 
     -DarchetypeArtifactId=hadoop-v1-mr
     -DarchetypeVersion=0.0.2-RELEASE
     -DgroupId=<my.groupid>
     -DartifactId=<my-artifactId>


##How to use it in eclipse?

1. Open eclipse
2. Open File->New->Maven project/Maven modules
3. Click "add archetype" button when you at the "Archetype choosing page"
4. Type  __org.stackbox.archetypes__ in __Archetype Group Id inputbox__, __webapp-ssm-basic__ in __Archetype Artifact id inputbox__, __0.0.2-RELEASE__ in __Archetype Version inputbox__, then click "Ok"
5. After all,you can select my archetypes in the archetype filter list
6. It's pretty the same when you want to add other artifact of mine
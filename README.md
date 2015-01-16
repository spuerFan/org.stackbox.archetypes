org.stackbox.archetypes
===

It's a set of maven3 archetypes during my career, with convenient usage.


##Create SSM Project


    mvn archetype:generate 
     -DarchetypeGroupId=org.stackbox.archetypes 
     -DarchetypeArtifactId=webapp-ssm-basic
     -DarchetypeVersion=0.0.1-SNAPSHOT
     -DgroupId=<my.groupid>
     -DartifactId=<my-artifactId>

##Create MR Project for Hadoop1.x

    mvn archetype:generate 
     -DarchetypeGroupId=org.stackbox.archetypes 
     -DarchetypeArtifactId=hadoop-v1-mr
     -DarchetypeVersion=0.0.1-SNAPSHOT
     -DgroupId=<my.groupid>
     -DartifactId=<my-artifactId>


##Create MR Project for Hadoop2.x

    mvn archetype:generate 
     -DarchetypeGroupId=org.stackbox.archetypes 
     -DarchetypeArtifactId=hadoop-v2-mr
     -DarchetypeVersion=0.0.1-SNAPSHOT
     -DgroupId=<my.groupid>
     -DartifactId=<my-artifactId>


##How to use it in eclipse?
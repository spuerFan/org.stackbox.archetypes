webapp-ssm-basic
=====================

It is a demo for maven archetypes plugin. We can use archetypes to generate our  project structs.



    mvn archetype:generate 
     -DarchetypeGroupId=<archetype-groupId> 
     -DarchetypeArtifactId=<archetype-artifactId> 
     -DarchetypeVersion=<archetype-version> 
     -DgroupId=<my.groupid> 
     -DartifactId=<my-artifactId>

mvn archetype:generate -DarchetypeGroupId=org.stackbox.archetypes  -DarchetypeArtifactId=webapp-ssm-basic -DarchetypeVersion=0.0.1-SNAPSHOT  -DgroupId=org.test -DartifactId=ssm
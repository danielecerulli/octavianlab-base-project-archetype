# octavianlab-base-project-archetype
Maven archetype which can be used to generate a multi module JavaEE 8 project in java 11

Compile project: mvn clean install

-------------------------------

mvn archetype:generate   
-DarchetypeGroupId=com.octavianlab.custom.archetype   
-DarchetypeArtifactId=octavianlab-base-project   
-DarchetypeVersion=1.0.0   
-DgroupId=com.dummy.project   
-DartifactId=new-dummy-project   
-DinteractiveMode=false   
-Dmodule1=my-custom-api   
-Dmodule2=my-custom-engine

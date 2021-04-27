# Import JAR with transitive dependencies



# Download dependencies into the /deps
´´´
mvn dependency:copy-dependencies -DoutputDirectory=deps -Dhttps.protocols=TLSv1.2
´´´

add param -Dclassifier=sources to include the sources. 

# Look the /deps folder
the dependencies will be downloaded into the ´/deps´ folder

### Use original firmata4j JAR dependency in pom.xml instead
By default the pom.xml package the latest commit of https://github.com/kurbatov/firmata4j into a .jar.
If you want to use a release instead change the pom.xml of this repository: 

Replace: 
´´´
...
<dependency>
	<groupId>com.github.kurbatov</groupId>
	<artifactId>firmata4j</artifactId>
	<version>master-SNAPSHOT</version>
</dependency>
...

´´´

With:

´´´
...
<dependency>
	<groupId>com.github.kurbatov</groupId>
	<artifactId>firmata4j</artifactId>
	<version>2.3.8</version>
</dependency>
...

´´´
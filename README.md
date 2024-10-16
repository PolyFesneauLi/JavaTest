# JavaTest

mvn archetype:generate -DgroupId=com.example \
-DartifactId=JavaTest \
-DarchetypeArtifactId=maven-archetype-quickstart \
-DinteractiveMode=false


first mvn clean 
thend mvn compile   or  mvn exec :java

mvn clean
mvn compile
mvn exec:java
mvn test

the test record in under path:
for MathTest:
JavaTest/target/surefire-reports/com.example.MathTest.txt
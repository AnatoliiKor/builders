# Maven
### Build and Run application

```shell script
# Clone project
git clone https://github.com/AnatoliiKor/builders.git

# Change the folder
cd builders

# build project
mvn clean package

# run Admin service
java -jar output/admin-1.0.0-jar-with-dependencies.jar

# run tests
mvn test 
```

# Gradle
### Build and Run application

```shell script
# Clone project
git clone https://github.com/AnatoliiKor/builders.git

# Change the folder
cd builders

# build project
gradle clean build

# run Admin service
java -jar outputGradle/admin-1.0.0-uber.jar

# run tests
gradle test 
```

### Run war-module
1. copy war-file from 'output*/web-1.0.0.war' to a {tomcat_install_dir}/webapps/
2. run tomcat-server ({tomcat_install_dir}/bin/startup.bat)
3. open in your browser http://localhost:8080/web-1.0.0/
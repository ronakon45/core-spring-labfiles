# Core Spring and Spring Boot Lab Projects

Labs for the Core Spring and Spring Boot courses

To import these labs into your IDE, import the parent pom `lab/pom.xml` as Maven projects or `lab/build.gradle` as Gradle projects.


# Build the Projects
Build the projects under core-spring-labfiles/lab directory. This will download and install required dependencies to local repository.

## Windows:
```
mvnw clean install
```

## MacOSX or Linux:
``` 
chmod 755 mvnw
```
```
./mvnw clean install
```

If you experience any build failure, check firewalls or proxy settings in the <Home-Directory>/.m2/settings.xml file.

# NOTE
- use java11 or java17 only for compile and build
- use Gradle only
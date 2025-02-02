# java-sample-maven


## Build the Project

Run the following Maven commands from the project root:

### Compile the Code:

`
mvn clean compile
`

### Package the Application:

`
mvn package
`
This creates a JAR file in the target directory, e.g., target/hello-world-1.0-SNAPSHOT.jar.

## Run the Application

After building the project, you can run the application in two ways:

### Directly with Maven:

`
mvn exec:java -Dexec.mainClass="com.example.HelloWorld"
`

## Simply the whole compile process with the command below

```
mvn clean install 
# then
java -jar target/hello-world-1.0-SNAPSHOT.jar
Output: Hello, World!
```

## Using the JAR File:

`
java -jar target/hello-world-1.0-SNAPSHOT.jar
`

## Output:

`
Hello, World!
`

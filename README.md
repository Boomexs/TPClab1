build:
mvn package
run:
cd into jar file,
java -cp my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
pmd:
mvn pmd:pmd # to install
mvn pmd:check

checkstyle:
mvn checkstyle:check

I don't think conflicts are that fun

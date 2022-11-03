# test-quarkus-release Project

This project is created to test if we can use the current Quarkus version to
push software to Maven Central.

## Building
```
mvn clean install
```

## Releasing to Maven Central.
```
mvn release:prepare release:perform
```

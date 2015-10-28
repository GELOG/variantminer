[![Stories in Ready](https://badge.waffle.io/GELOG/variantminer.png?label=ready&title=Ready)](https://waffle.io/GELOG/variantminer)
# variantminer

[![Join the chat at https://gitter.im/GELOG/variantminer](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/GELOG/variantminer?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
A web UI over genomic data


## Installation
#### Requirements
* Java 1.8.0_45 (tested on OpenJDK)
* Scala 2.10.4
* Maven 3.3.3

#### Compilation
```
mvn package -Dmaven.test.skip=true
```

## Using
To run the program, do:
```
scala target/variantminer-0.1-SNAPSHOT-jar-with-dependencies.jar
```
or
```
java -jar target/variantminer-0.1-SNAPSHOT-jar-with-dependencies.jar
```

## Troubleshooting
```
mvn clean
```
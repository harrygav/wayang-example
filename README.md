# wayang-examples

This repository contains some examples for Apache Wayang (incubating).
To run the examples, make sure that you have maven and Java 11 installed, and that your `$JAVA_HOME` path points to the right installation, e.g.:

```
echo $JAVA_HOME
/usr/lib/jvm/java-11-openjdk-amd64
```

To run a particular example class through maven, for example the `WordCountJava` class, execute the following:

```
mvn compile exec:java -Dexec.mainClass="examples.WordCountJava"
```

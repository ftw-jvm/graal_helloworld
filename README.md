# GraalVM - native image

## Compiling and running
```
$ javac HelloWorld.java
$ native-image HelloWorld
$ ./helloworld
```
or
```
mvn package
```
After you build with maven, you can view the dashboard!
https://www.graalvm.org/dashboard/
# maven-mojo-template
Small template project for building Maven Plugins


# How to run example
First make sure plugin is compiled and installed into the local maven repository

```
cm-maven-plugin/mvn install
```

Then compile the provided example project, notice how the plugin is executed and does print "hello world"

```
cm-maven-plugin-tester/mvn compile
```

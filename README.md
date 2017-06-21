# Jenkins template for Groovy Plugin


This repo contains a template to build Groovy Plugin. Gradle is being used as a build tool.

To build the plugin
```
./gradlew build
```

This will generate build/libs/hello-world-groovy.hpi. Install the plugin in jenkins. This will add a Build step called "say Hello"

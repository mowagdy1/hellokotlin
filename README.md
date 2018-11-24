# Hello World with Kotlin

A simple HelloWorld backend app with Kotlin language using [Gradle](https://gradle.org) and [Ktor](http://ktor.io).

 
### Running the app 

Each sample can be run with 

```
./gradlew :<sample-name>:run
```

Then navigate to [http://localhost:8080/](http://localhost:8080/) to see the result.  
 
Some samples require additional setup as explained in their readme files.
   
## Compact directory layout

Samples use compact directory layout whenever possible for ease of navigation:

* `src` directory contains sources directly (no `src/main/kotlin` and package directories).
* `resources` directory contains resources.
* `webapp` directory contains `WEB-INF` directory for samples that are deployed as WARs.

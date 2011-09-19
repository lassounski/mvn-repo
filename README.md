Lassounski Maven Repository
===========================

This is a repository where I maintain my maven projects that can be used inside any maven application.

Usage
----------

Suppose you are willing to use the PubMedDataset-1.0-SNAPSHOT in your project.

In your project pom.xml:

* Add to the following code to ```xml<repositories>```:
```xml
    <repositories>
    ...
        <repository>
            <id>lassounski-snapshots</id>
            <url>https://github.com/lassounski/mvn-repo/raw/master/snapshots</url>
        </repository>
    ...
    </repositories>
```

* And add the name and version of the project you want to use in ```xml<dependecies>```:
```xml
    <dependencies>
        ...
        <dependency>
            <groupId>com.uenf</groupId>
            <artifactId>PubMedDataset</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
        ...
    </dependencies>
```
That`s it, the .jar will be automatically downladed to your project dependencies and will be ready to use.



### Introductory paper:
*[A Coq-based synthesis of Scala programs which are correct-by-construction](http://dl.acm.org/citation.cfm?doid=3103111.3104041)*

### Quick start guide:

First, download the Scala Build Tool (SBT) from http://www.scala-sbt.org/download.html

Then, in the project's main directory run the command ```sbt assembly```

Finally, the below command:

```scala target/scala-2.12/scallina-assembly-<scallina-version>.jar <path-to-coq-source-file.v>```

can be executed from the project's main directory in order to run Scallina.

Also, the below command should also work:

```java -jar target/scala-2.12/scallina-assembly-<scallina-version>.jar <path-to-coq-source-file.v>```

### Usage Examples

Packaged examples are available under [```packaged-examples```](./packaged-examples)

Additional examples of Coq ```.v``` files that can be translated to Scala are available under [```src/test/resources/```](./src/test/resources/)

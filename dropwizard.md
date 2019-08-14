## Dropwizard

<http://www.dropwizard.io/1.1.4/docs/getting-started.html>

Jetty HTTP
Jackson JSON
Metrics for metrics
Guava immutable data structures
JDBI for database interaction
liquibase - database refactorings instead of one off DDL statements
Maven

JavaBeans standard - id and content properties

"Jersey resources are the meat-and-potatoes of a Dropwizard application"

AtomicLong - thread-safe way of generating fairly unique IDs

@Timed annotation

`Optional.of("Dougie") # wtf?`


threads resource, get a thread dump of all running threads

maven-shade

signed dependencies?

fat jars to ease deployment
versioning your jar


`brew install maven`

Generate project configuration
`mvn archetype:generate -DarchetypeGroupId=io.dropwizard.archetypes -DarchetypeArtifactId=java-simple -DarchetypeVersion=1.0.0`


What is the difference between all of these? what is a group? what is an artifact? what is a package?

<https://maven.apache.org/guides/mini/guide-naming-conventions.html>

package? (same as groupId?)
artifactId same as "name"?


<https://dzone.com/articles/getting-started-dropwizard>


<http://www.dropwizard.io/1.1.4/docs/>


mvn clean (holding on to old config file?)

mvn package

mvn-repo
========

A "maven" repository for compiled versions of my libraries

Hot to use it
--------

In your pom.xml, add the following repository:

```xml
<repository>
	<id>my-ideas.mvn.repo</id>
	<url>https://raw.github.com/totomz/mvn-repo/master</url>
	<snapshots>
		<enabled>true</enabled>
		<updatePolicy>always</updatePolicy>
	</snapshots>
</repository>
```

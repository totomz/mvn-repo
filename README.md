
A "maven" repository for compiled versions of my libraries. Artifacts are published in the branch `gh-pages`!

# Usage
Simply add this repo to your 
```xml
<repositories>
  <repository>
    <id>totomz-github</id>
    <name>Totomz  maven repo</name>
    <url>http://totomz.github.com/mvn-repo/repository/</url>
  </repository>
</repositories>
```

# Deploy artifacts

1. clone this repo and `git fetch && git checkout gh-repo`
2. Set the distribution management in the pom
```xml
<distributionManagement>
  <repository>
    <id>gh-pages</id>
    <url>file:///${mvn-repo-dir}/repository/</url>
  </repository>
</distributionManagement>
```

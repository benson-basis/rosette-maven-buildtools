# Basis Maven Buildtools #

This project publishes checkstyle and PMD rules to Maven, so that they
can be reused in multiple projects using the maven-checkstyle-plugin
and maven-pmd-plugin.


```
mvn release:prepare
mvn releaes:perform
  --OR--
mvn release:perform -Darguments=-Dgpg.passphrase=MY_PASSPHRASE
```

Login to https://s01.oss.sonatype.org/ and release from staging.

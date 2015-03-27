build:
```
mvn clean install -DskipTests
```

usage:
```
java -jar deb-repo-query-1.1.one-jar.jar <uri> [<package-spec>] [<architecture>]
```

example:
```
java -jar deb-repo-query-1.0.one-jar.jar http://in.archive.ubuntu.com/ubuntu/dists/saucy/main/binary-amd64 gcc
```

use dist/deb-repo-query-1.0.jar to use it as a library with your project. you will need to add sqlite-jdbc-3.7.2, commons-io-2.4 & commons-codec-1.10 jars along with this jar.

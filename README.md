# Usage:

- Clone this repository
- cd kafka-debian
- ./build.sh VERSION REVISION
- dpkg -i ./kafka_0.8.1.1-1.deb

```
An Ubuntu/Debian packaging script for Apache Kafka

USAGE: ./build.sh VERSION REVISION

./build.sh 0.8.1.1 1

VERSION: the Kafka release version (eg: 0.8.1.1)
REVISION: the revision number to use when generating the .deb (eg: 1)
```

# Dependencies:

- aptitude install openjdk-7-jre
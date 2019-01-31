[<img src="https://sling.apache.org/res/logos/sling.png"/>](https://sling.apache.org)

 [![Build Status](https://builds.apache.org/buildStatus/icon?job=Sling/sling-org-apache-sling-nosql-launchpad/master)](https://builds.apache.org/job/Sling/job/sling-org-apache-sling-nosql-launchpad/job/master) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![nosql](https://sling.apache.org/badges/group-nosql.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/groups/nosql.md)

# Apache Sling NoSQL Launchpad

This module is part of the [Apache Sling](https://sling.apache.org) project.

Variant of the Sling Launchpad to run NoSQL Resource Providers in standalone mode.

To run with NoSQL MongoDB resource provider:

```
java -Dsling.run.modes=nosql-mongodb -jar target/org.apache.sling.nosql.launchpad-1.0.0-SNAPSHOT.jar -c sling -f -
```

To run with NoSQL Couchbase resource provider:

```
java -Dsling.run.modes=nosql-couchbase -jar target/org.apache.sling.nosql.launchpad-1.0.0-SNAPSHOT.jar -c sling -f -
```

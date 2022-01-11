[![Apache Sling](https://sling.apache.org/res/logos/sling.png)](https://sling.apache.org)

&#32;[![Build Status](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-nosql-launchpad/job/master/badge/icon)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-nosql-launchpad/job/master/)&#32;[![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-nosql-launchpad&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-nosql-launchpad)&#32;[![Contrib](https://sling.apache.org/badges/status-contrib.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/status/contrib.md)&#32;[![nosql](https://sling.apache.org/badges/group-nosql.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/groups/nosql.md) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

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

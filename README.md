# ElasticSearch Client OSGi Bundle

This bundle wraps the [ElasticSearch Client](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/index.html) into an OSGi Bundle for easier deployment.

## Installation

You can build this bundle from source using Maven:

    mvn clean install

To install it into an [Apache Sling](http://sling.apache.org/) Environment (or AEM), use the sling:install command:

    mvn sling:install -Dsling.url=http://localhost:PORT/system/console



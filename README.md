# ElasticSearch Client OSGi Bundle

This bundle wraps the [ElasticSearch Client](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/index.html) into an OSGi Bundle for easier deployment.

Note:
This bundle depends on some libraries, espacially the [Apache HttpClient](https://hc.apache.org/) which has to be be available in version `4.5.2`. See in the official [documentation](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/_dependencies.html) for more info.
So currently this bundle is not compatible with AEM up to 6.2 (with 6.3 most likely a new version will be included).

## Installation

You can build this bundle from source using Maven:

    mvn clean install

To install it into an [Apache Sling](http://sling.apache.org/) Environment (or AEM), use the sling:install command:

    mvn sling:install -Dsling.url=http://localhost:PORT/system/console


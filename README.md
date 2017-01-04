# ElasticSearch Client OSGi Bundle

This bundle wraps the [ElasticSearch Client](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/index.html) into an OSGi Bundle for easier deployment.

See my Blogpost for more details: [https://www.dev-eth0.de/blog/2017/01/04/elasticsearch-rest-osgi.html](https://www.dev-eth0.de/blog/2017/01/04/elasticsearch-rest-osgi.html)

## Installation

You can build this bundle from source using Maven:

    mvn clean install

To install it into an [Apache Sling](http://sling.apache.org/) Environment (or AEM), use the sling:install command:

    mvn sling:install -Dsling.url=http://localhost:PORT/system/console



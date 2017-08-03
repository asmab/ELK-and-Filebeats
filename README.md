# Docker ELK stack

ELK (Elasticsearch, Logstash, Kibana) stack with Docker and Docker Compose.

Aanalyze any data with Elasticsearch and the visualization with Kibana.

Based on the official Docker images:

* [elasticsearch](https://github.com/elastic/elasticsearch-docker)
* [logstash](https://github.com/elastic/logstash-docker)
* [kibana](https://github.com/elastic/kibana-docker)

Kibana [http://localhost:5601](http://localhost:5601) with a web browser.

Ports by default:
* 5000: Logstash TCP input.
* 9200: Elasticsearch HTTP
* 9300: Elasticsearch TCP transport
* 5601: Kibana

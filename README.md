## Elasticsearch and Kibana in one container

Simple and lightweight docker image for previewing Elasticsearch and Kibana.

### Usage

    docker run -d -p 9200:9200 -p 5601:5601 nshou/elasticsearch-kibana

Then you can connect to Elasticsearch by `localhost:9200` and its Kibana front-end by `localhost:5601`.

### Tags

Tag     | Elasticsearch | Kibana
------- | ------------- | ------
latest  | 6.2.1         | 6.2.1
kibana5 | 5.6.6         | 5.6.6
kibana4 | 2.4.1         | 4.6.2
kibana3 | 1.7.4         | 3.1.3

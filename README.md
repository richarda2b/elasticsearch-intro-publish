# Introduction to Elasticsearch

This is a practical introduction to elasticsearch. It contains basic examples and exercises to get started.

## Prerequisites

You will need couple tools to complete the practical exercises,
choose one of the two options to set up your environment.

### Using docker (recommended)

  1. Install docker(if not already installed): [official doc](https://store.docker.com/editions/community/docker-ce-desktop-mac)
  2. Excecute `./auto/start.sh`
  3. Verify elasticsearch is running:`curl localhost:9200`
  4. Navigate to `http://localhost:5061` in your browser to verify that kibana is running

### Manual installation (the long road)

  Elasticserch:
  1. Download [elasticsearch 5.6.3](https://www.elastic.co/downloads/elasticsearch)
  2. Extract it into yor prefered location.
  3. Start elasticsearch `<extracted-location>/bin/elasticsearch`
  4. Verify that it is running: `curl localhost:9200`

  Kibana:
  1. Download [kibana](https://www.elastic.co/downloads/kibana)
  2. Extract it into yor prefered location
  3. Open `<extracted-location>/config/kibana.yml`
  5. Start kibana `<extracted-location>bin/kibana`
  6. Navigate to `localhost:5061` in your browser

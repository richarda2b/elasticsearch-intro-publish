# Introduction to Elasticsearch

This is a practical introduction to elasticsearch. It contains basic examples and exercises to get started.

## Prerequisites

You will need a couple tools to complete the practical exercises,
choose one of the two options to set up your environment.

The presentation slides can be found [here](https://richarda2b.github.io/elasticsearch-intro-publish/)

### Using docker (recommended)

  1. Install docker(if not already installed): [official doc](https://store.docker.com/editions/community/docker-ce-desktop-mac)
  2. Excecute `./auto/start.sh`
  3. Verify elasticsearch is running:`curl localhost:9200`
  4. Navigate to `http://localhost:5601` in your browser to verify that kibana is running

To stop elasticsearch just run `./auto/stop.sh`

### Install on your machine

  Elasticserch:
  1. Download [elasticsearch 6.2.2](https://www.elastic.co/downloads/past-releases/elasticsearch-6-2-2)
  2. Extract it into yor prefered location.
  3. Start elasticsearch `<extracted-location>/bin/elasticsearch`
  4. Verify that it is running: `curl localhost:9200`

  Kibana:
  1. Download [kibana](https://www.elastic.co/downloads/past-releases/kibana-6-2-2)
  2. Extract it into yor prefered location
  3. Open `<extracted-location>/config/kibana.yml`
  5. Start kibana `<extracted-location>bin/kibana`
  6. Navigate to `localhost:5601` in your browser

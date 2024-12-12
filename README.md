# Getting started with the Elastic Stack and Docker-Compose

This repo is in reference to the blog [Getting started with the Elastic Stack and Docker-Compose](https://www.elastic.co/blog/getting-started-with-the-elastic-stack-and-docker-compose)

Please feel free to ask any questions via issues [here](https://github.com/elkninja/elastic-stack-docker-part-one/issues), our [Community Slack](https://ela.st/slack), or over in our [Discuss Forums](https://discuss.elastic.co/).

Pull Requests welcome :)


## Some Addition Steps

sudo chown root:root ./filebeat.yml

sudo chmod 600 ./filebeat.yml

sudo chown root:root ./metricbeat.yml

sudo chmod 600 ./metricbeat.yml

### Update these values to avoid memory errors
ES_MEM_LIMIT=6073741824
KB_MEM_LIMIT=2073741824
LS_MEM_LIMIT=1073741824

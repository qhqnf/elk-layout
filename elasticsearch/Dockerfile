FROM docker.elastic.co/elasticsearch/elasticsearch:7.9.3

# Install korean anaylsis tool nori
RUN elasticsearch-plugin install analysis-nori

# Copy config file
WORKDIR /usr/share/elasticsearch
COPY ./config/elasticsearch.yml ./config/elasticsearch.yml
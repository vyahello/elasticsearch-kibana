FROM docker.elastic.co/elasticsearch/elasticsearch:7.0.0

RUN mkdir /home/elasticsearch-backup
RUN chown -R elasticsearch:elasticsearch /home/elasticsearch-backup

COPY --chown=elasticsearch:elasticsearch elasticsearch.yml /usr/share/elasticsearch/config/

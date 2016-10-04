FROM elasticsearch:latest
MAINTAINER james.leech@tattsgroup.com

RUN /usr/share/elasticsearch/bin/plugin install royrusso/elasticsearch-HQ
RUN /usr/share/elasticsearch/bin/plugin install lmenezes/elasticsearch-kopf

EXPOSE 9200 9300

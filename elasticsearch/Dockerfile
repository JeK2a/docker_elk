FROM docker.elastic.co/elasticsearch/elasticsearch:7.14.2
COPY --chown=elasticsearch:elasticsearch ./elasticsearch.yml /usr/share/elasticsearch/config/hunspell/en_US/en_US.dic
COPY --chown=elasticsearch:elasticsearch ./elasticsearch.yml /usr/share/elasticsearch/config/hunspell/en_US/en_US.aff
COPY --chown=elasticsearch:elasticsearch ./elasticsearch.yml /usr/share/elasticsearch/config/hunspell/ru_RU/ru_RU.dic
COPY --chown=elasticsearch:elasticsearch ./elasticsearch.yml /usr/share/elasticsearch/config/hunspell/ru_RU/ru_RU.aff

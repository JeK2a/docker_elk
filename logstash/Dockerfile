FROM docker.elastic.co/logstash/logstash:7.14.2
COPY ./mysql-connector-java-5.1.48-bin.jar /usr/share/logstash/
COPY ./logstash.yml /usr/share/logstash/config/
COPY ./logstash.conf /usr/share/logstash/pipeline/
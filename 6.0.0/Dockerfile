FROM docker.elastic.co/logstash/logstash-oss:6.0.0
COPY logstash.conf /some/config-dir/
WORKDIR /usr/share/logstash
CMD ["-f", "/some/config-dir/logstash.conf"]
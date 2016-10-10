FROM logstash:latest

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

COPY ./config/ /etc/logstash/conf.d/

CMD ["-f", "/etc/logstash/conf.d/logstash.conf"]

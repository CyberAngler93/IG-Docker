  
FROM influxdb:latest

LABEL author="Matt Perry"
LABEL description="InfluxDB for IG"

USER root

ADD influxdb.conf /influxdb.conf

ADD run.sh /run.sh
RUN chmod +x /run.sh

CMD ["/run.sh"]
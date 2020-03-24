FROM debian:9.5-slim

RUN chmod +x entrypoint.sh
ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ['/entrypoint.sh']

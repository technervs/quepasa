# Build stage
FROM golang:1.20.2 as quepasa-source

WORKDIR /opt/quepasa-source/

COPY . /opt/quepasa-source/

RUN chmod 755 /opt/quepasa-source/docker/docker-entrypoint.sh
RUN sed -i 's/\r//' /opt/quepasa-source/docker/docker-entrypoint.sh
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

ENTRYPOINT ["/opt/quepasa-source/docker/docker-entrypoint.sh"]
CMD ["sh"]
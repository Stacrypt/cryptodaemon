FROM kp666/bitcoincash-docker

RUN echo "#bitcoind.conf" >> /opt/bitcoinabc/bitcoind.conf && \
    echo "datadir=/opt/bitcoinabc/data" >> /opt/bitcoinabc/bitcoind.conf

COPY docker-entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]

CMD ["bitcoind"]

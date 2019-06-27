FROM kp666/bitcoincash-docker

#COPY bitcoind.conf /opt/bitcoinabc/bitcoind.conf
COPY docker-entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]

CMD ["bitcoind"]

FROM jryberg/mosquitto-exporter:v0.7.9@sha256:a68104c040a398426ee1f93187bdf9f66f482092cfcd51333462907d25c03550

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD [ "/mosquitto_exporter" ]

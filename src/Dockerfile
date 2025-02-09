FROM jryberg/mosquitto-exporter:v0.7.4@sha256:09a5cc8518b61f5b83bc93f6e51ff5c0a331ffc258293f28384b26969f99c82a

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD [ "/mosquitto_exporter" ]

FROM jryberg/mosquitto-exporter:v0.7.3

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD [ "/mosquitto_exporter" ]

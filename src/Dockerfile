FROM jryberg/mosquitto-exporter:v0.7.5@sha256:b765da6aa4fef18e47f622e83fb802ec781ac62b26ffc50a60bde0dd37d2873d

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD [ "/mosquitto_exporter" ]

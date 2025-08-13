FROM jryberg/mosquitto-exporter:v0.7.7@sha256:8c32d6ca22cefdbff011809096b0b2e52dbd646c59f9199ef4cc467a3d66e0cd

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD [ "/mosquitto_exporter" ]

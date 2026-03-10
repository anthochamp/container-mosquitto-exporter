# Mosquitto Exporter Container

![GitHub License](https://img.shields.io/github/license/anthochamp/container-mosquitto-exporter?style=for-the-badge)
![GitHub Release](https://img.shields.io/github/v/release/anthochamp/container-mosquitto-exporter?style=for-the-badge&color=457EC4)
![GitHub Release Date](https://img.shields.io/github/release-date/anthochamp/container-mosquitto-exporter?style=for-the-badge&display_date=published_at&color=457EC4)

Container images based on [mosquitto-exporter](https://github.com/jryberg/mosquitto-exporter), a Prometheus exporter for Eclipse Mosquitto MQTT broker metrics.

## How to use this image

```shell
docker run -p 9234:9234 \
  -e BROKER_ADDRESS=tcp://mqtt-broker:1883 \
  anthochamp/mosquitto-exporter
```

## Port

| Port   | Protocol | Description                 |
| ------ | -------- | --------------------------- |
| `9234` | TCP      | Prometheus metrics endpoint |

## Configuration

This container adds Docker secrets support: append `__FILE` to any environment variable name to read its value from a file (e.g., `MQTT_PASS__FILE=/run/secrets/mqtt_password`).

All environment variables supported by mosquitto-exporter are available. Refer to the [mosquitto-exporter documentation](https://github.com/jryberg/mosquitto-exporter#configuration) for the full list.

## References

- [mosquitto-exporter on GitHub](https://github.com/jryberg/mosquitto-exporter)
- [Eclipse Mosquitto](https://mosquitto.org/)
- [Prometheus](https://prometheus.io/)

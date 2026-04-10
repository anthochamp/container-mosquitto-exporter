# Mosquitto Exporter Container Images

Container images based on [mosquitto-exporter](https://github.com/jryberg/mosquitto-exporter), a Prometheus exporter for Eclipse Mosquitto MQTT broker metrics.

Sources are available on [GitHub](https://github.com/anthochamp/container-mosquitto-exporter).

See [README.md](README.md) for full documentation and configuration reference.

## Image tags

- `x.y.z-exporterA.B.C`: Container image version `x.y.z` with mosquitto-exporter `A.B.C`.
- `edge-exporterA.B.C`: Latest commit build with mosquitto-exporter `A.B.C`.

**Tag aliases:**

- `x.y-exporterA.B.C`: Latest patch of `x.y` with mosquitto-exporter `A.B.C`.
- `x-exporterA.B.C`: Latest minor+patch of `x` with mosquitto-exporter `A.B.C`.
- `x.y.z-exporterA.B`: Version `x.y.z` with latest patch of mosquitto-exporter `A.B` (only latest container version updated).
- `x.y-exporterA.B`: Latest patch of `x.y` with latest patch of mosquitto-exporter `A.B`.
- `x-exporterA.B`: Latest minor+patch of `x` with latest patch of mosquitto-exporter `A.B`.
- `x.y.z-exporterA`: Version `x.y.z` with latest minor+patch of mosquitto-exporter `A` (only latest container version updated).
- `x.y-exporterA`: Latest patch of `x.y` with latest minor+patch of mosquitto-exporter `A`.
- `x-exporterA`: Latest minor+patch of `x` with latest minor+patch of mosquitto-exporter `A`.
- `x.y.z`: Version `x.y.z` with latest mosquitto-exporter (only latest container version updated).
- `x.y`: Latest patch of `x.y` with latest mosquitto-exporter.
- `x`: Latest minor+patch of `x` with latest mosquitto-exporter.
- `exporterA.B.C`: Latest container with mosquitto-exporter `A.B.C`.
- `exporterA.B`: Latest container with latest patch of mosquitto-exporter `A.B`.
- `exporterA`: Latest container with latest minor+patch of mosquitto-exporter `A`.
- `latest`: Latest `x.y.z-exporterA.B.C` tag.
- `edge-exporterA.B`: Latest commit build with latest patch of mosquitto-exporter `A.B`.
- `edge-exporterA`: Latest commit build with latest minor+patch of mosquitto-exporter `A`.
- `edge`: Latest `edge-exporterA.B.C` tag.

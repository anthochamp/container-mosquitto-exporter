# TODO — container-mosquitto-exporter

## Tests

- [ ] `tests/index.ts` is empty — there are **no tests**.
  - Add an integration test that starts a Mosquitto broker (via `testcontainers`) alongside this exporter container, then issues an HTTP `GET /metrics` and asserts that Mosquitto-specific metric names are present (e.g., `mosquitto_clients_connected`).
  - Add a test verifying that the container exits if it cannot connect to the broker (bad host/port), rather than silently retrying forever.

## Health Check

- [ ] Confirm whether a HEALTHCHECK is present. If not, add one — e.g., `wget -qO- http://localhost:9234/metrics | grep mosquitto || exit 1`.

## Documentation

- [ ] `CONTAINER.md`: document env vars for broker address, port, username/password, and TLS configuration.
- [ ] Document what metrics are exported and link to the upstream `mosquitto_exporter` metrics reference.

## Maintainability

- [ ] See [COMMON-TODO.md](../COMMON-TODO.md) for `.github/workflows/`, OCI labels, `.dockerignore`, `replaceEnvSecrets` extraction, and dep version alignment.

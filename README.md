# 🖋 Signet

Signet is Omni's provenance-first e-signature service: sign documents with a
cryptographically verifiable signature and a tamper-evident provenance trail,
self-hostable and freely embeddable across Omni products.

Live at [signet.omni.dev](https://signet.omni.dev).

This metarepo orchestrates Signet's services for local development with
[Tilt](https://tilt.dev).

- Signet API: https://github.com/omnidotdev/signet-api

## Getting Started

`cp services.yaml.template services.yaml`, then configure the services as
needed. To disable a service, comment it out. Included services are cloned
locally; a `path` key overrides the clone location.

```sh
tilt up
```

## License

The code in this repository is licensed under Apache 2.0, &copy;
[Omni LLC](https://omni.dev).

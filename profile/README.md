# Helix: A Flexible and Scalable NextGen Cellular Core

Helix is a scalable, cloud-native 5G core that improves control-plane performance while keeping the flexibility of the
3GPP Service-Based Architecture. It scales network functions independently through UE-aware load balancing,
distributed state management and per-UE state caching, and recovers from network-function failures while keeping
per-UE state consistent. Helix is based on [OMEC / SD-Core](https://github.com/omec-project).

**Start here:** [`helix`](https://github.com/Helix-NextGen-Cellular-Core/helix) deploys Kubernetes, the Helix core and
the gnbsim load generator, and runs experiments.

## Repositories

| | Repositories |
|---|---|
| Testbed and experiments | [`helix`](https://github.com/Helix-NextGen-Cellular-Core/helix) |
| Network functions | [`amf`](https://github.com/Helix-NextGen-Cellular-Core/amf) · [`smf`](https://github.com/Helix-NextGen-Cellular-Core/smf) · [`sctplb`](https://github.com/Helix-NextGen-Cellular-Core/sctplb) · [`nrf`](https://github.com/Helix-NextGen-Cellular-Core/nrf) · [`udm`](https://github.com/Helix-NextGen-Cellular-Core/udm) · [`udr`](https://github.com/Helix-NextGen-Cellular-Core/udr) · [`ausf`](https://github.com/Helix-NextGen-Cellular-Core/ausf) · [`pcf`](https://github.com/Helix-NextGen-Cellular-Core/pcf) · [`nssf`](https://github.com/Helix-NextGen-Cellular-Core/nssf) |
| Load generator | [`gnbsim`](https://github.com/Helix-NextGen-Cellular-Core/gnbsim) (branch `realtrace` for real-trace workloads) |
| Libraries | [`util`](https://github.com/Helix-NextGen-Cellular-Core/util) · [`nas`](https://github.com/Helix-NextGen-Cellular-Core/nas) · [`mongodblibrary`](https://github.com/Helix-NextGen-Cellular-Core/mongodblibrary) |

## Images

Release `v1.0.0`: `ghcr.io/helix-nextgen-cellular-core/<name>:v1.0.0` (see
[Packages](https://github.com/orgs/Helix-NextGen-Cellular-Core/packages)). Each network-function repository builds its
image with `docker build .`

Licensed under Apache-2.0.

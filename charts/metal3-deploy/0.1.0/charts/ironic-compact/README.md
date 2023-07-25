## Ironic compact deployment

Demonstrate a compact Ironic deployment with the following constraints:

- Uses the [combined ironic launcher](https://github.com/metal3-io/ironic-image/pull/330) to avoid separate API/conductor processes and related RPC
- No provisioning network or PXE support (could be added if required)
- Use sqlite instead of mariadb, no PVC (ephemeral DB)
- Intended for single-replica use only, so a [limit to simultaneous provisioning](https://github.com/metal3-io/baremetal-operator/pull/725) is likely to be required at large scale
- Only supports ingress, no support for hostNetwork/external-dns
- TLS support is still TODO


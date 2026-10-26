# Somnia StopLoss Guardian AI — System Architecture & Topology

## Executive Overview
**Somnia StopLoss Guardian AI** (`$SOMSTOP`) is a sovereign Web4 protocol engineered for the **Somnia Network** ecosystem under the **Security** domain.

```
       +------------------------------------------------+
       |             Client / Frontend UI               |
       +-----------------------+------------------------+
                               |
                               v
       +------------------------------------------------+
       |     MCP Invariant RPC Gateway (Somnia Network)        |
       +-----------------------+------------------------+
                               |
            +------------------+------------------+
            |                                     |
            v                                     v
+-----------------------+             +-----------------------+
|  Deterministic Rust   |             |  NIST FIPS 203 / 204  |
|     State Engine      |             |   Cryptographic Vault |
+-----------------------+             +-----------------------+
```

## Security Invariants
- 10,000 cycle deterministic state transition boundary.
- Zero private key capture policy in frontend forms.

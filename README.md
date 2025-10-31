# pqproto

**pqproto** is a practical framework for experimenting with **post-quantum cryptography (PQC)** in real-world security protocols.  
It provides command-line–based client–server prototypes for both classical and PQ-secure communication. The core libraries and tools used are:

- [OpenSSL](https://github.com/openssl) with PQC support (v3.5.0 & above)
- [liboqs](https://github.com/open-quantum-safe/liboqs) and [oqs-provider](https://github.com/open-quantum-safe/oqs-provider) for hybrid/PQ key exchange and signatures
- [strongSwan](https://github.com/strongswan/strongswan) for IPsec integration
- [Circl](https://github.com/cloudflare/circl) and other PQC libraries for algorithm diversity

## Protocols Covered

- TLS / mTLS
- DTLS
- QUIC
- IPsec
- OAuth
- SSH  
  (More coming soon)

## Prerequisites

- [OpenSSL 3.5.2](./docs/install-openssl.md) with post-quantum support
- GCC with C11 support
- pkg-config (`sudo apt install pkg-config`) for dynamic library path configuration

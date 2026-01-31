# Docker-FTPS
Isolated FTPS deployment using Docker Compose, designed for secure file storage and centralized management in a containerized sandbox.

[**PT-BR**](./docs/README.pt-br.md)

## Dependencies
- [Docker Installation](https://www.docker.com/products/docker-desktop/)

## Roadmap
- [x] Research and define base image (`stilliard/pure-ftpd`)
- [ ] Build MVP (Minimum Viable Product) FTPS service
- [ ] Implement and test CIA security principles:
    - [ ] **Confidentiality**: SSL/TLS encryption (The "S" in FTPS)
    - [ ] **Integrity**: Persistent storage and volume mapping
    - [ ] **Availability**: Docker Compose orchestration

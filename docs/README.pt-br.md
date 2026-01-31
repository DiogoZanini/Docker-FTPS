# Docker-FTPS
Implantação de FTPS isolado utilizando Docker Compose, projetado para armazenamento seguro de arquivos e gerenciamento centralizado em um sandbox conteinerizado.

[**EN-US**](../README.md)

## Dependências
- [Instalação do Docker](https://www.docker.com/products/docker-desktop/)

## Roadmap (Cronograma)
- [x] Pesquisar e definir imagem base (`stilliard/pure-ftpd`)
- [ ] Construir o MVP (Produto Mínimo Viável) do serviço FTPS
- [ ] Implementar e testar os princípios de segurança CIA:
    - [ ] **Confidencialidade**: Criptografia SSL/TLS (O "S" do FTPS)
    - [ ] **Integridade**: Armazenamento persistente e mapeamento de volumes
    - [ ] **Disponibilidade**: Orquestração via Docker Compose

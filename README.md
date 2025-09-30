# Tarefa Docker 1 - MongoDB

---

## Requisitos

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) instalado e rodando.
- Git para clonar o repositório (opcional).

Para verificar a instalação:

- docker --version
- docker compose version

## Como rodar o projeto

Clone este repositório ou baixe os arquivos:

- git clone https://github.com/seu-usuario/seu-repositorio.git
- cd seu-repositorio

Suba o container:

- docker compose up -d

Verifique se o container está rodando:

- docker ps

## Conexão externa

O MongoDB estará disponível na porta 27017 da sua máquina.
Para conectar de fora (por exemplo, MongoDB Compass ou outro cliente):

- mongodb://admin:admin123@localhost:27017


Se for conectar de outra máquina na mesma rede, use o IP da sua máquina:

- mongodb://admin:admin123@<IP_DA_SUA_MAQUINA>:27017

## Credenciais

- Usuário: admin
- Senha: admin123
- Porta: 27017

## Encerrar o servidor

Para parar os containers:

- docker compose down

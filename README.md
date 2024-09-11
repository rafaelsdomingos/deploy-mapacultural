![Logo Mapacultural](https://mapacultural.secult.ce.gov.br/assets/img/logo-ceara-2396208294-1680122696.png)

# Instalação do Mapa Cultural do Ceará

## 1. Pré-requisitos

### Hardware:

### Software:

* curl
* docker
* docker compose plugin

## 2. Download

Crie um diretório para salvar os arquivos do mapacultural
```
mkdir mapacultural && cd mapacultural
```

Baixe o arquivo do docker compose com a configuração de todos os containers utilizados e o arquivo .env:

```
curl -O https://raw.githubusercontent.com/rafaelsdomingos/deploy-mapacultural/main/mapacultural/compose.yaml && curl -O https://raw.githubusercontent.com/rafaelsdomingos/deploy-mapacultural/main/mapacultural/.env
```

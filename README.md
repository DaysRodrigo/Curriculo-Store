# Curriculo-Store

Este repositório contém o **docker-compose** para rodar localmente o projeto **Curriculo-Store**, composto por:

- **Frontend**: React (`curriculo-store.client`)
- **Backend**: .NET (`Curriculo-store.Server`)

> Os repositórios de frontend e backend são separados e não estão incluídos neste repo.

---

## Pré-requisitos

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) instalado na máquina
- Git (para clonar os repositórios front e back)

---


## Como rodar localmente

1. Clone este repositório e os repositórios do frontend e backend dentro das pastas indicadas:

```bash
git clone https://github.com/DaysRodrigo/Curriculo-Store
cd Curriculo-Store
git clone https://github.com/DaysRodrigo/Curriculo-store.Client curriculo-store.client
git clone https://github.com/DaysRodrigo/Curriculo-store.Server Curriculo-store.Server
```

2. Suba os containers com Docker Compose:

```bash
docker compose up --build
```

3. Acesse:

Frontend: http://localhost:8080

Backend: http://localhost:5000

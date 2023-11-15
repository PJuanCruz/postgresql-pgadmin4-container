![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

# 📰 Guide

### 1. Make sure you have Git and Docker installed by running the following commands:

```bash
$ git -v
```

```bash
$ docker -v
```

### 2. Clone the repository and move to the project directory:

```bash
$ git clone https://github.com/PJuanCruz/postgresql-pgadmin4-container.git
```

```bash
$ cd postgresql-pgadmin4-container
```

### 3. Start the Docker container:

```bash
docker compose up -d
```

### 4. Connect PgAdmin4:

- [127.0.0.1:[PGADMIN_PORT]](http://127.0.0.1/)

<img src="./public/img/img-1.png" alt="Alt text" width="400"/>

- Email Address / Username: [PGADMIN_EMAIL]

- Password: [PGADMIN_PASSWORD]

<img src="./public/img/img-2.png" alt="Alt text" width="400"/>

<img src="./public/img/img-3.png" alt="Alt text" width="400"/>

- Name: PostgreSQL

<img src="./public/img/img-4.png" alt="Alt text" width="400"/>

- Host name/address: [Service Name]

- Port: [PG_PORT]

- Maitenance database: [PG_DATABASE]

- Username: [PG_USER]

- Password: [PG_PASSWORD]

<img src="./public/img/img-5.png" alt="Alt text" width="400"/>

### 5. Stop and remove containers and networks:

```bash
docker compose down
```

# MySQL Docker Template

Template MySQL menggunakan Docker Compose.

## Persyaratan

- Docker Engine / Docker Desktop
- Docker Compose

## Clone Repository

```bash
git clone https://github.com/username/mysql-docker.git
```

Masuk ke folder

```bash
cd mysql-docker
```

Copy file environment

```bash
cp .env.example .env
```

Jalankan container

```bash
docker compose up -d
```

Cek status

```bash
docker ps
```

## Akses MySQL

Host

```
localhost
```

Port

```
3306
```

Database

```
mydatabase
```

Username

```
myuser
```

Password

```
mypassword
```

## Login melalui Terminal

```bash
docker exec -it my-mysql mysql -u root -p
```

## phpMyAdmin

Buka browser

```
http://localhost:8080
```

Host

```
mysql
```

Username

```
root
```

Password

```
root
```

## Stop Container

```bash
docker compose down
```

## Stop + Hapus Volume Database

```bash
docker compose down -v
```

## Jalankan Kembali

```bash
docker compose up -d
```

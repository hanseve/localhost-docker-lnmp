# localhost-docker-lnmp
A Simple Docker LNMP (Nginx + PHP + Mysql + Redis) for Localhost

## Use it
Make dir 'data/mysql' 'data/redis'，Where mysql and redis data stored.
```
mkdir -p data/mysql
mkdir data/redis
```
Start services
```
docker-compose up -d
```
Then you can open `http://localhost/`, and see phpinfo page.


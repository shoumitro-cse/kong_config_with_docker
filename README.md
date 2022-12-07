# kong_config_with_docker


## jwt url
```

# admin GUI url
http://localhost:8002

# admin listen url
http://localhost:4001/consumers/login-server/jwt

# Proxy base url
http://localhost:4000

```


## setup

```
sudo systemctl start docker
docker stop kong-gateway-dbless
docker rm kong-gateway-dbless
docker-compose up --build

```
# mongodb-master-slave-demo
MongoDB Master-Slave Demo

## Launch servers

```sh
$> docker-compose up -d
```

## Create default network

```sh
$> docker network create --driver=bridge --subnet=192.168.200.0/24 --gateway=192.168.200.1 local-network
```

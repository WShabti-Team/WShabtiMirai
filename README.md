Rete di container Docker per lo studio della botnet Mirai.

##### Building
```
cd docker-bot
sudo docker build -t bot .
```

```
cd docker-cnc
sudo docker build -t cnc .
```

##### Esecuzione

```
docker-compose up --scale bot=<NUM_OF_BOTS>
```

by WShabti Team
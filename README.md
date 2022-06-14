![image](https://user-images.githubusercontent.com/45710698/173601062-403108c5-3f77-4aae-b66a-589ac0909b44.png)

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

# Mirai Source Code 
https://github.com/jgamblin/Mirai-Source-Code

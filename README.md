## Create Docker volumes for local storage

```docker volume create ollama
docker volume create open-webui
docker volume create open-webui
```



## Start docker compose

```
docker compose up -d
```

## Execute the model

```
docker exec -it ollama ollama run llama3.2
```



### Note


This is for amd gpus only

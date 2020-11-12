### Добавление node в swarm

```
1. docker swarm init
2. docker service create --name registry --publish published=5000,target=5000 registry:2
3. docker-compose up -d
4. docker-compose push
5. docker stack deploy --compose-file docker-compose.yml flask-app
6. docker stack services flask-app
```

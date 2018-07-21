1. Pull repository to any `directory`
2. On the same level with that `directory` create `applications` folder
3. Create a copy of `.env-example`, rename it to `.env` and fill up variables
4. Go to the `directory` and run `docker-compose up -d`

```
docker inspect <container id> | grep "IPAddress"
```

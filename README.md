# Docker-Compose for the PHP project

You should have Docker Desktop installed before starting it.
## Run docker-compose from project root folder
```bash
docker-compose up
```

Open [localhost:4010](http://localhost:4010) in your browser to see the "hello world"

## Change the application port
Stop docker;
Open docker-compose.yaml, change the port 4010 to 8000 (or set your value)
```bash
docker-compose up
```
Check your app at the new port.

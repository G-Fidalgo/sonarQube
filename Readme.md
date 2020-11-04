# SonarQube Instance with volume persistance

This repo stores the necessary information to lunch a SonarQube instance with volume persistance

## First run this commands on your terminal to avoid crash on startup

```bash
sysctl -w vm.max_map_count=262144
sysctl -w fs.file-max=65536
```

## Run docker-compose command to start up

```bash
docker-compose up -d
```
# Hacking LAB using Docker on Cloud (GCP)

![Banner Image](https://raw.githubusercontent.com/thehackersbrain/kalivnc/refs/heads/main/screenshots/kalivnc.png)

- On GCP Console (with custom configuration)
```bash
git clone https://github.com/thehackersbrain/dockerhackinglab.git && cd dockerhackinglab
docker-compose up -d -f docker-compose.yaml
```

- On GCP Console (with custom configuration)
```bash
git clone https://github.com/thehackersbrain/dockerhackinglab.git && cd dockerhackinglab
docker-compose up -d -f docker-compose-web.yaml
```

- For stopping the lab
```bash
docker ps # for getting all running containers
docker-compose down # for stopping the lab
# or
docker-compose down --rmi all  # for removing the lab
```

If you used `docker-compose.yaml` file with custom configurations

> `:1` is for 5901 and display `:1` and the default password is `kalikali`

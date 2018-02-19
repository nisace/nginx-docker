This project is a very simple example of how to set up Nginx with Docker.

# Installation
`git clone https://gitlab.com/docker-webapp/nginx-docker.git`

# Run
```
cd nginx-docker
docker-compose up
```

# Run in background
```
cd nginx-docker
docker-compose up -d
```

Once launched, the application is available at [localhost:80](localhost:80)

# Stop the application running in background
`docker-compose down`



#etant dans le dossier planner :  docker build -t planner . -f DockerFile.planner

#image dans le port: docker run --network=mynetwork --name planner -p 3000:3000 -d planner
#execute : sh build.sh



#etant dans le dossier worker : docker build -t worker . -f Dockerfile.worker

#image dans le port: docker run --network=mynetwork --name worker -p 8080:8080 -d worker

# docker run --network=mynetwork --name worker1 -e PORT=8070 -d worker
#execute : sh build.sh

# Dockerfile for Worker

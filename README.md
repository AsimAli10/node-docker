# node-docker
This is a simple hello world node project along with Dockerfile to for a making it a docker application and deploying it on Docker Hub.

## Steps to run this docker
- clone this repo or download it as zip folder and open it on VS Code.
- Open the terminal and run following commands(make sure you have docker desktop installed and working. Also Yo ushould have signed in at Docker Hub).
  - "docker build -t node-docker ." {you can verify by accessing the the application on browser on 'localhost:3000'}
  - docker tag node-docker <username>/<repository>:<tag> {your dockerhub username, dockerhub reporsitory and tag of your choice (you can use docker-hub)}.
  - docker push <username>/<repository>:<tag>
  - docker run -p 3000:3000 <username>/<repository>:<tag>
  - Now you can access the the application on browser on 'localhost:3000'.
- Congratulations, your docker is pushed on dockerhub and it is running on your desktop you. You can close the container using Docker Desktop or CLI.
  

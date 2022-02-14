# react-app-dockerized

## Run and build app

docker build -t react-tutorial-2022:latest .

docker run --name react -v "$(pwd)/src:/app/src" -v "$(pwd)/public:/app/public" -p 3000:3000 react-tutorial-2022

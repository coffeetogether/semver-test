# Node.js Docker starter
The most basic boilerplate using Node.js, Express and Docker.

## Run
1. Clone this repo
2. Install deps: `npm i`
3. Build image: `docker build -t nodejs-docker-starter .`
4. Run image: `docker run -p 3000:3000 -d --name nds nodejs-docker-starter:latest`
5. Go to http://localhost:3000

## Run test
1. `npm test`

## Other docker commands
- Show running containers: `docker ps`
- Show app logs: `docker logs nds`
- Stop app: `docker rm -f nds`

## Author
- [Davide Violante](https://github.com/DavideViolante)

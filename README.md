# Koa-API

## Get Started
Address, port needs to be modified

```bash
cd koa-api-example
npm install
npm run dev
```


## Usage
Use postman or API tools to access the restFul API inside of it
Every thing are inside of 'server_db.js'

## Some Useful docker command
This will initiate a container for mongodb
`<addr>`docker run --name mongo -e MONGO_INITDB_ROOT_USERNAME=mongo -e MONGO_INITDB_ROOT_PASSWORD=sct2head -v $(pwd)/mongo:/data/db -d -p 38017:27017 --rm mongo:latest

This will create a node container for backend to run with
docker run -itd -p 8080:8080  -v ~/playground/GitoDo:/data --name nodejs node
This gets you into container
docker exec -it nodejs /bin/bash

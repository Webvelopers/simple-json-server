# Simple JSON Server
This project is a Simple JSON Server without need implement back-end server, only using NodeJS and [JSON Server](https://github.com/typicode/json-server) (NodeJS module)

## Project Requirements (2022-01-10):
- NodeJS >= v14.18.0
- NPM >= v6.14.15
- JSON Server (NodeJS Module) >= v0.17.0
- Visual Studio Code >= V1.63.2 (or other code editor)

## Instructions:
You only need:
- a) Clone this repo or b) Create this project
- Run NPM script
- Test Simple JSON Server

### a) Clone this repo and install NodeJS modules
``` bash
git clone https://github.com/Webvelopers/simple-json-server.git
cd simple-json-server
npm update
```

### b) Create this repo in only 3 easy steps

#### 1. Install json-server with NPM
``` bash
npm install json-server
```

#### 2. Create package.json file
``` bash
code package.json
```

#### 3. Copy and paste this json text
``` json
{
    "scripts": {
        "start": "json-server --watch db.json"
    }
}
```

### Run NPM script
``` bash
npm start
```

### Test Simple JSON Server
``` bash
start http:localhost:3000
```

## Official Documentacion of JSON Server (NodeJS module)
Go to github official repo: [JSON Server](https://github.com/typicode/json-server)

## Enjoy It!
```
made with ♥ by...
    __    __
    \/\/\/\/
     \/\/\/
      \/\/
www.webvelopers.net
```

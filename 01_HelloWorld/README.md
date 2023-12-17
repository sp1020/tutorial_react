# Lession 1. Hello World 

Create a simple Node.js application that display a messege 'Hello world' via web. 

Node.js(`node`) launches a web service on port `3000` on address `127.0.0.1`. 

## 1. Create a JavaScript code 

Open a Javascript file in the `01_HelloWorld` directory with the name `server.js`, and write the script below in it. 

    const http = require("node:http");
    const hostname = "127.0.0.1";
    const port = 3000;
    const server = http.createServer((req, res) => {
    res.statusCode = 200;
    res.setHeader("Content-Type", "text/plain");
    res.end("Hello World\n");
    });
    server.listen(port, hostname, () => {
    console.log(`Server running at http://${hostname}:${port}/`);
    });

The code is from the Node.js official site: 
* https://nodejs.org/en/learn/getting-started/introduction-to-nodejs

## 2. Run the server 

In terminal, move to the `01_HelloWorld` directory and execute the following command.

    node server.js

In VSC, press `Go Live` buttom to stream the server into a local (127.0.0.1) 

## 3. Connect to the server in the brower

Access the web page with the following address 

`http://127.0.0.1:3000/`



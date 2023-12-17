# tutorial_react

Tutorial for using React 


## Introduction 

React is a JavaScript library specified for front-end development.

A web or HTML page is a document consisted of multiple components having the Document Object Model (DOM) structure. The page can be actively modified by JavaScript programs that respond to events. 

React is a JavaScript library that can facilitate to design JavaScript to handle events. 

In this tutorial, we will create a React application. 

1. Build a React application
2. Deploy the application 


## Setup 

### Node.js and npm

Install node.js and npm. 

(*) If you are not a system administrator, consult with the administrator.

Node.js and npm can be installed as follows. 

    sudo apt-get update
    sudo apt-get install -y ca-certificates curl gnupg
    sudo mkdir -p /etc/apt/keyrings
    curl -fsSL https://deb.nodesource.com/gpgkey/nodesource-repo.gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/nodesource.gpg
    NODE_MAJOR=20
    echo "deb [signed-by=/etc/apt/keyrings/nodesource.gpg] https://deb.nodesource.com/node_$NODE_MAJOR.x nodistro main" | sudo tee /etc/apt/sources.list.d/nodesource.list
    sudo apt-get update
    sudo apt-get install nodejs -y
    
(*) Consult with server administrator if you are not a `sudo` user. 

### Visual Studio Code

Install Visual Studio Code in the desktop

* Live Server - to launch application in remote server as local machine 
* prettier - to beautify the code

## Lessons 

* [01_HelloWorld](./01_HelloWorld/README.md) - Create a simple Node.js application





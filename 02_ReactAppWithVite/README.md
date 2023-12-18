# Lecture 2. Creating Application using Vite template

Vite is a build tool for application development. It generates a template project creating files and directory structures. We can create react applications using and modifying Vite template.

You can 

https://vitejs.dev/guide/


* This tutorial is created based on the following documents.
  * https://youtu.be/SqcY0GlETPk?si=PX49PWGPG1BZLQI6

## 1. Create a react application using Vite 

### 1-1. Create a project template using Vite.

    cd 02_Vite
    npm create vite@4.1.0

Enter the following input values to create a React template.

* Project name: react-app
* Framework: React
* Variant: TypeScript

### 1-2. Install

Install the required libraries using `npm`.

    cd react-app
    npm install 

### 1-3. Run the server 

Execute the following command to run the server.

    npm run dev

## 2. Create a simple messege react component 

In `react-app/src/` create `Message.tsx` file. 

Open the file and add a function. 

    // A component (function)
    function Message() {
        //JSX: JavaScript XML
        return <h1>Hello world</h1>
    }

    export default Message

The `<h1>Hello world</h1>` part is not HTML, it is JavaScript XML, which will be compiled into JavaScript. 

The conversion from JavaScript XML to JavaScript can be tested in the web-site https://babeljs.io/repl. 

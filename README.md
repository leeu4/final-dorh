# Basic Expressjs Server #
in this repo you will learn how to make a basic express js server using typescript

## First Step ##

install nodejs from [nodejs.org](https://nodejs.org)
after downloading nodejs download typescript using command below
```
npm i typescript
```
## Second Step ##
### Making tsconfig.json ###
open cmd and type 
```
npx tsc --init
```
## tsconfig configuration ##
Search for rootDir and out dir in tsconfig remove the comment in rootDir type src , type dist in outDir
Make src folder make typescript file in it.
## package.json install ##
just open the cmd and type to install package.json
```
npm init -y 
```
## express and type install ##
open cmd type the commands below 
```
npm i express  //to install express 
npm i @types/express //to install @types
```
## Start building the server using express and typescript ##
start by importing express in the ts file 
```
import express from 'express'
const app = express()
const PORT = 3000;

app.listen(PORT,()=>{
    console.log("server is running on port",PORT);
});

```
the code above will make a basic server with out anything
## social media accounts ##
[twitter](https://twitter.com/sa_fah9)
[instagram](https://instagram.com/leeu_992)

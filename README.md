# Basic Expressjs Server #
you need to download typescript and express [npm](https://www.npmjs.com/)
and nodejs
##First Step##
install tsconfig.json by using npx tsc --init
##Second Step##
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
## Start building the server using express and type express ##
start by importing express in the ts file 
```
import express from 'express'
const PORT = 3000
const app = express()

```

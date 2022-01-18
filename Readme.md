# Prerequisites
You must install mongodb locally using Docker

```
docker pull mongo
```


# You must to install the following modules before start

```
$ npm install typescript express concurrently mongoose bcrypt morgan axios

$ npm install nodemon dotenv -D

$ npm install @types/concurrently @types/mongoose @types/morgan @types/bcrypt @types/typescript @types/express -D
```

# Usage
Once you have installed all the Node/Tyscript modules to iniciate the program run the following script
```
npm run dev
```
# Build
This software was build with: 
```
'adidas-api-product-service': '1.0.0',
  npm: '8.3.0',
  node: '14.16.1',
  v8: '8.4.371.19-node.18',
}
```
# To Run this API
You must consider the following with Insomnia Project attached:
1. Create a user:
```
POST: localhost:4001/api/auth/signup
```
Response will be an JWT and the JWT must be used to call CRUD APIs






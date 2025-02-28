# Building a Scalable Node.js API in 10 Minutes

Node.js is one of the best choices for building scalable APIs due to its event-driven, non-blocking architecture.\
In this guide, we'll set up a fast and scalable API using Express.js in just 10 minutes.

## 1. Setup Your Project

First, initialize a new Node.js project and install dependencies:

![image](https://github.com/user-attachments/assets/defe390b-be57-42ea-b6d4-70d18bb466ff)

+ **express**: Minimalist framework for building APIs.

+ **dotenv**: Loads environment variables from a .env file.

+ **cors**: Enables Cross-Origin Resource Sharing.

+ **helmet**: Adds security headers to requests.

+ **morgan**: Logs incoming requests for debugging.

# 2. Create the Server

Create an index.js file and set up a basic Express server:

![image](https://github.com/user-attachments/assets/51337b5e-508f-421d-9d5a-0b90853ddeb7)

# 3. Add Environment Variables

Create a .env file to manage configurations:
Add below line

**PORT=5000**

In **just 10 minutes**, we've built a **scalable and secure Node.js** API with Express.js. From here,\ 
you can expand it with database connections **(MongoDB, PostgreSQL), authentication (JWT, OAuth),\
and caching (Redis, Memcached)** for even better performance.

make sure to upgrade your node version if you are using node 10.0.0 or below version it will throw below error when running the application

![image](https://github.com/user-attachments/assets/9fda5bd2-51a7-4c82-bff8-89c6485a1123)

when you are doing changes to existing files each time you have to restart the server, to prevent this you can install nodemon for this.
once installed, you just need to start the sever by 
**npm start**, it will allows real time updates.

***you can download the repository from here: [Building a Scalable Node.js API in 10 Minutes](https://github.com/piumidinuka/scalable-node-api.git)***


## 4. Organize Your API

![image](https://github.com/user-attachments/assets/038c57ed-2773-4888-b93d-f3d29d2db3a4)

## 5. Deploy & Scale

+ Use PM2 for process management:

![image](https://github.com/user-attachments/assets/533e24c9-abee-4b87-b39f-97b5c51b201f)

+ Use Docker for containerization.

+ Use a Load Balancer for scaling across multiple instances.





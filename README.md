# NodeJs, Express, EJS & MongoDB Blog - CRUD

![alt text](/readme-image.jpg?raw=true)

## You need:
- NodeJs
- Database (MongoDB) Free Cluster

## Create .env file
Create a .env file to store your credentials. Example below:

```
MONGODB_URI=mongodb+srv://<username>:<password>@clusterName.xxxxxxx.mongodb.net/blog
JWT_SECRET=MySecretBlog
```

## Installation
To install and run this project - install dependencies using npm and then start your server:

```
$ npm install
$ npm run dev
```

## Design Files
The Blog layout is available in a Figma(.fig) file located under the "Design Files".

[View Live Figma Prototype](https://www.figma.com/proto/Vpc5J1ajnwDTT96q0IUFDJ/NodeJs-Blog?page-id=0%3A1&type=design&node-id=48-119&viewport=-194%2C377%2C0.17&scaling=min-zoom&starting-point-node-id=48%3A119)


## Features
- User Registration
- User Login
- User Logout
- User Profile
- Blog Posts
- Blog Post Creation
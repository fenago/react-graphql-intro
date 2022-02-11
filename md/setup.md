#### Local Setup Guide

**Using docker**

1. Install Docker: https://docs.docker.com/engine/install/
2. Pull Docker Image: `docker pull fenago/react-graphql-intro`
3. Start Lab Environment: 
`docker run -d --privileged --restart=always --user root -p 80:80 -p 81:81 -p 3000:3000 -p 8000:8000 -p 5900:5900 --name graphqlintro fenago/react-graphql-intro`

**Optional:**

* Restart Lab Environment: 

`docker restart graphqlintro`

* Delete Lab Environment: 

```
docker stop graphqlintro
docker rm graphqlintro
```

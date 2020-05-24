# Vue-cli4 with Docker

## Structure
```
vue-test
├── docker
│   └── Dockerfile
├── docker-compose.yml
└── app
```

## Build
```bash
$ git clone git@github.com:zakbutchy/vue-test.git

$ docker-compose build
$ docker-compose up -d

$ docker-compose exec app sh

# If you want to create a new application, run the following command inside the container.
/usr/src/app # vue create .
# Choose preset and package manager.

# run
/usr/src/app # npm run serve
```

**Access**  
http://localhost:8080

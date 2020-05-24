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


## app

### Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

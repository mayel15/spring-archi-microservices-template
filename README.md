# 🩻 Spring Archi Microservices Template

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/mayel15/node-express-template)

👨🏾‍💻 Pape THIAM [@mayel15](https://github.com/mayel15)

# 🧰 Stack

<a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="100" height="100"/> </a> <a href="https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/" target="_blank" rel="noreferrer"> <img src="https://imgs.search.brave.com/oTzlZ5o5m_C3Bn4S6L-2Pv6f6xuJJo8bD39DgWJZaDg/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9jZG4t/aW1hZ2VzLTEubWVk/aXVtLmNvbS9tYXgv/ODAwLzEqZ3hYTE1J/dUpESENIN2Z3SWdF/UDFjZy5wbmc" alt="springboot" width="175" height="100"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="100" height="100"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="100" height="100"/> </a> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="100" height="100"/> </a>

## ➕ More

- Cloud Config
- Eureka Server
- APi Gateway

# 📄 Description du projet

This is an opinionated boilerplate (template or skeleton, whatever you want) for SpringBoot architecture oriented microservices. This repository serves as a template to simplify the [creation of new repositories from it](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).

# ⚙️ Clean, Compile, Package

- In the project, a `.jar` file will be generate for each microservices for the builds of docker images

- In case of sources files changements, **compile** and **package** the concerned microservice project with `maven` in order to get the `.jar` file for building new `docker image`

- Highly recommended to do it for each microservice

# 🚀 Run

- Clone the projet

```sh
git clone https://github.com/mayel15/spring-archi-microservices-template.git
```

- Run the microservices with `docker` at the root of the project

```sh
cd spring-archi-microservices-template
```

```sh
docker-compose up -d
```

- Wait until the complete launch of all the microservices present in the `docker-compose`

- Eureka server will run in `localhost` at the port `9102`

![alt text](readme-images/eureka-server-overview.png)

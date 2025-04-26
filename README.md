The system serves as an address management platform that allows users to validate and search address records through a modular, scalable backend.

Key Contributions
Developed and implemented modular backend services for address validation and search workflows.

Integrated RESTful APIs and database interactions to ensure accurate and formatted address responses.

Containerized backend services with Docker and orchestrated deployments using Kubernetes for scalable, isolated testing.

Collaborated in a 4-member Agile team following sprint-based coordination, peer code reviews, and system design discussions.

Technologies Used
Backend: Java, Spring Boot
Database: SQL/PostgreSQL
Deployment: Docker, Kubernetes
Version Control: Git, GitHub
Frontend: Basic form-based UI for request handling

# Prerequisites

Make sure you have the following software installed on your development machine:
* Java 17 (LTS)
* Docker (version 27.5.1 or later)
* Docker Compose (version 2.12.2 or later)
* Apache Maven (version 3.9.9 or later)
* GNU Make (version 3.81 or later)
* 
To verify your installations, run:
```bash
java --version
docker --version
docker-compose --version
mvn --version
make --version

```

# How to Contribute
## 1. Develop and Test Locally

   Make your changes in the repository.
   From the project’s root folder, start the MySQL container and run the Spring Boot application:
```bash
make run
```


After you finish testing, stop and remove the local database container:
```bash
    make down
```


## 2. Deploy Multiple Containers

If you need to spin up all containers (MySQL, the Dockerized API, and an admin container for MySQL):

Deploy the services:
```bash
  make deploy
```
 

Once you’re done, clean up everything:
```bash
make destroy

```
    

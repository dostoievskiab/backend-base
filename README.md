# Simple Backend
Building a simple RESTful API using:
- Express
- Sequelize
- PostgreSQL

### What am i trying to learn?
- Version Control of Database (Migrations...)
- TDD with JEST 

### Creating development database
I will be using Docker to run the postgreSQL 
First step is to download the image from Docker HUB
> docker pull postgres

Then you need run it with the configuration
> docker run --name bd_dev -e "POSTGRES_PASSWORD=Teste123*" -p 5432:5432 -d postgres

Now the Postgres is accessible from port 5432, if needed you can access the cli of the container with:
> docker exec -it bd_dev bash

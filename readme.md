# Rails Microservices

Running Rails with Microservices Architecture using Docker Containers.

The following containers will be run by default:
- application (for storing project source code)
- workspace (for working around with the all project)
- mysql
- mysql_test (for running integration test)
- mongodb
- redis
- data (for storing `mysql`, `mongo`, `redis` data)

## Usage
- Copy file `docker-compose.yml` to your Laravel folder.
- You should change the `project` keyword with your real project name in `docker-compose.yml` file.
- You can change other database and container names as well.
- Run `docker-compose up` and enjoy.
- If you do not need any services (such as `mongodb` or `redis`), simply remove it from `docker-compose.yml`

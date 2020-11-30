# Laravel docker

Basic setup for Laravel with docker

## Setup
1. Install docker and docker-compose.
2. Clone this repo
3. Add Laravel project to the "app" directory
4. From the root of the project, run `docker-compose build` to build php image
5. Run `docker-compose up -d` to run project, and access from localhost:8000
6. To enter workspace enter `docker-compose exec workspace bash` from root. Simply run `exit` to quit.
7. Build stuff!

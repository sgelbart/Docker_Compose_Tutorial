# Docker_Compose_Tutorial

- Install docker and docker-compose for your OS. On Mac this one single, simple install. Windows and Linux require additional effort.
- Clone this repo: `git clone https://github.com/codeformuskogee/Docker_Compose_Tutorial.git`
- CD to working directory `cd Docker_Compose_Tutorial`
- `sudo docker-compose up`
- To get the name of your images use: `sudo docker images` for names of containers use: `sudo docker containers`
- To connect to shell use: `sudo docker exec -it dockercomposetutorial_db_1 bash` where `dockercomposetutorial_db_1` is the name of your process. 

Other notes
- Build docker from docker file: `docker build --it path/to/docker/file .`
- Run docker from image: `docker run -it yourimagename`

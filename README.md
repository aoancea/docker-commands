# docker-commands
- connect to bash in docker container: `docker exec -it sql1 bash`
- path to database files: `cd /var/opt/mssql/data`
- copy file from docker to host: `docker cp {container_name}:{path_to_file_from_docker} {path_to_folder_on_host}`
- copy file from host to docker: `docker cp {path_to_folder_on_host} {container_name}:{path_to_file_from_docker}`

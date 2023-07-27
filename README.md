# launch_hive_in_docker
all command all in one


Step 1: Clone GitHub repo
GitHub link: https://github.com/big-data-europe/docker-hive


Step 2: Open with VS Code
Open the new terminal in VS Code


Step 3: Run docker-compose.yml file command
Command: docker-compose up -d


Step 4: Check Docker list of files command
Command: docker container ls


Step 5: Run the command for execution (docker image: Hive server that is copied from the Docker Hive server image)
Command: docker exec -it 94797ff3e497ef726e743d3a1ef397029edc79cfd876f5d4bb1805705b9e56c4 /bin/bash


Step 6: Run these commands on /opt/hive directory
Command: /opt/hive/bin/beeline -u jdbc:hive2://localhost:10000


# launch_hive_in_docker
all command all in one


step 1: clone git hub repo
git hub link:  https://github.com/big-data-europe/docker-hive
step 2: open with the vs code
open the new terminal in vs code
step 3: run docker-compose. yml file
command: - docker-compose up -d
step 4: check docker lis t of file
command: docker container ls
step 5: run the command for execution (docker image: hive server that is copy from the docker hive server image)
command: docker exec -it 94797ff3e497ef726e743d3a1ef397029edc79cfd876f5d4bb1805705b9e56c4 /bin/bash

step 6:run these command on /opy3
command: /opt/hive/bin/beeline -u jdbc:hive2://localhost:10000

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


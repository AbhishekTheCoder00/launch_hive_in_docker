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

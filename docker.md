# docker commands

> Start the docker service "sudo service docker start/stop/restart"

> Build docker "docker build [OPTIONS] PATH | URL | -"

> Checking the running container "docker ps"

> Remove the running container "docker rm $(docker ps -a -q)"

> Checking the running images "docker images"

> Remove the running images "docker rmi $(docker images -q)"

> Grep the process "ps -ax | grep processname"

> Kill the process "sudo killall processname"

> Check the open network "netstat -a | grep ':http'"

> Killing the port "sudo kill $(sudo lsof -t -i:portname)"

> List all listening ports  "sudo netstat -lnp"

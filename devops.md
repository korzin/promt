## Docker: 
1. Commands

| Name, shorthand | Default | Description | Command |
|---|---|---|---|
| --tty, -t  | false  |  Allocate a pseudo-TTY |exec |
|--detach, -d	| false	| Detached mode: run command in the background |exec |
|--detach-keys	 ||	Override the key sequence for detaching a container | exec|
|--env, -e	 ||	Set environment variables | exec|
|--interactive, -i | false |	Keep STDIN open even if not attached |exec |
|--privileged |	false	|Give extended privileges to the command |exec |
|--user, -u	| 	|Username or UID (format: <name&#124;uid>[:<group&#124;gid>]) | exec |
2. Tips

|Commands |Desctiption |
|---|---|
|docker exec -it container_name bash  | Shell into the already running docker container. |
|docker stop $(docker ps -a -q)| Stop all containers at once |
|docker rm $(docker ps -a -q)| Remove all containers at once |
|docker build -t image_name .  |Build image from Dockerfile in corr folder|
|docker run -d -p 8080:8080 image_name| Run container from image |

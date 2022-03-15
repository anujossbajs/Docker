## Docker Exercises
- Task 1 - Docker installation on Linux
- Task 2 - Create a Docker file with below details.
Copy index.php to /tmp. Copy build.yaml to / . Install packages "which" and "net-tools" . Set JAVA_HOME to /usr. Run bash shell as PID 1. Build the docker image. Create a container from it.           
- Task 3 - Run Nginx webserver in a container using dockerfile 
- Task 4 - Create a local registry . Push the nginx image from previous task into the local Registry.
Remove the image from the local cache and Pull the image from the local registry.Push the image into the Docker Hub.
- Task 5 - Create a Docker Compose YAML file with 2 services sshd and a webserver.For ssh create a user "student" with password "student" . Map the container port to host port 2222. For webserver use nginx image from docker hub .
Run the image using docker compose.

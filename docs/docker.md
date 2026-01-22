
### Day 0 – Docker Basics
- Docker is a containerization tool that packages applications with dependencies.
- Core concepts include images, containers, and Dockerfiles.

## Day 1 – Docker Architecture
- Client–daemon model
- Docker daemon manages containers
- Docker client issues commands
- Images stored in registries
- Docker Hub is default

## Day 1 – Docker Architecture
- Client–daemon model
- Docker daemon manages containers
- Docker client issues commands
- Images stored in registries
- Docker Hub is default

## Day 1 – Docker Architecture
- Client–daemon model
- Docker daemon manages containers
- Docker client issues commands
- Images stored in registries
- Docker Hub is default

## Day 1 – Docker Architecture
- Client–daemon model
- Docker daemon manages containers
- Docker client issues commands
- Images stored in registries
- Docker Hub is default

## Day 1 – Docker Architecture
- Client–daemon model
- Docker daemon manages containers
- Docker client issues commands
- Images stored in registries
- Docker Hub is default

## Day 1 – Docker Architecture
- Client–daemon model
- Docker daemon manages containers
- Docker client issues commands
- Images stored in registries
- Docker Hub is default

## Day 1 – Docker Architecture
- Client–daemon model
- Docker daemon manages containers
- Docker client issues commands
- Images stored in registries
- Docker Hub is default

## Day 0 – Docker Basics
- Docker packages apps with dependencies
- Containers are lightweight vs VMs
- Solves environment inconsistency
- Fast startup and portability
- Core DevOps foundation

## Day 1 – Docker Architecture
- Client–daemon model
- Docker daemon manages containers
- Docker client issues commands
- Images stored in registries
- Docker Hub is default

## Day 2 – Docker Installation
- Native on Linux
- Uses VM on Windows/macOS
- docker --version verifies install
- hello-world validates setup
- Docker Desktop manages resources

## Day 3 – Docker Images
- Read-only templates
- Built in layers
- Cached for performance
- Smaller images are faster
- docker images lists them

## Day 4 – Containers
- Running instance of image
- Ephemeral by default
- docker ps shows running
- docker ps -a shows all
- Can start/stop/remove

## Day 5 – Docker Commands
- docker run creates containers
- docker exec runs commands inside
- docker logs for debugging
- docker rm removes containers
- docker stats monitors usage

## Day 6 – Dockerfile Basics
- Blueprint for image creation
- Each instruction is a layer
- FROM defines base image
- RUN executes build commands
- CMD runs container process

## Day 7 – Dockerfile Instructions
- WORKDIR sets path
- COPY transfers files
- ENV defines variables
- EXPOSE documents ports
- ENTRYPOINT defines executable

## Day 8 – Dockerfile Best Practices
- Order layers for caching
- Minimize image size
- Avoid root user
- Clean package cache
- Use .dockerignore

## Day 9 – Building Images
- docker build creates images
- -t tags image
- Build context matters
- Cache speeds rebuilds
- .dockerignore improves speed

## Day 10 – Tagging Images
- Tags identify versions
- latest is default
- Semantic versioning preferred
- Same image can have many tags
- docker tag renames

## Day 11 – Docker Registries
- Store and distribute images
- Docker Hub is public
- docker login authenticates
- docker push uploads images
- docker pull downloads

## Day 12 – Logs & Monitoring
- docker logs shows output
- docker stats shows usage
- Useful for debugging
- Monitor CPU & memory
- Improves reliability

## Day 13 – Docker Volumes
- Persist container data
- Survive container removal
- Managed by Docker
- Used for databases
- Share data across containers

## Day 14 – Volume Types
- Named volumes preferred
- Bind mounts for development
- Anonymous volumes discouraged
- docker volume ls lists
- docker volume prune cleans

## Day 15 – Docker Networking
- Enables container communication
- Bridge is default network
- Containers use names not IPs
- Improves security
- docker network ls

## Day 16 – Custom Networks
- Automatic DNS resolution
- Better isolation
- Easier service discovery
- docker network create
- Avoid port conflicts

## Day 17 – Multi-Container Apps
- Apps split into services
- Database not exposed
- Internal communication only
- Env vars configure services
- Microservice friendly

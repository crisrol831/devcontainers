# Dockerfile for local development

Steps to create local devcontainer

1. `docker pull <base-image>`
2. `docker run <image>`
3. connect your vscode and install all plugins and libraries need for development
4. `docker commit <container_name> <image_name>`
5. create docker-compose.yml
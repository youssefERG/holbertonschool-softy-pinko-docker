# Start from the newest Ubuntu image available on Docker Hub
FROM ubuntu:latest

# Refresh Ubuntu's list of available software
RUN apt-get update

# Upgrade software already included in Ubuntu
RUN apt-get upgrade -y

# The command that runs automatically when the container starts
CMD ["echo", "Hello, World!"]
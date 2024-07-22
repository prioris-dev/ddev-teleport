# Use the official DDEV web service as the base image
FROM drud/ddev-webserver

# Install Teleport client
RUN apt-get update && apt-get install -y curl && \
    curl https://goteleport.com/static/install.sh | bash -s 15.4.0 oss

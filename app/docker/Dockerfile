FROM postman/newman:latest

WORKDIR /etc/newman

# Copy collections and environment files
COPY collections ./collections
COPY env ./env

# Run Newman with desired reporters
CMD ["newman", "run", "SimpleCollection.json", "-e", "global.json", "-r", "cli,json,html,htmlextra"]
FROM postman/newman:latest

WORKDIR /etc/newman

COPY collections ./collections

CMD ["run", "collections/SimpleCollection.json"]
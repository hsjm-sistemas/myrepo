docker run --name mongodb -d -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=user -e MONGO_INITDB_ROOT_PASSWORD=pass -v $(pwd)/data:/data/db mongodb/mongodb-community-server:$MONGODB_VERSION

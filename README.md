# Docker base image with dependencies

Docker image with following dependencies

1. numpy==1.14.3
2. pymongo==3.6.0
3. pandas==0.23.3
4. neo4j_driver==1.5.3
5. Flask==0.12.2
6. neo4j==1.7.1
7. scikit-learn==0.20.0
8. scipy==0.19.1

## Build command

  docker build -t py36-pred-db-sync --no-cache .

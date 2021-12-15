# Currency Exchange API – NodeJS

docker run -d -p 8080:8080 u1ih/nodejs-api

curl -i http://localhost:8080/fx





# NUSFintech DevOps Project

## Steps
1) Forked from github.com/hellojoechip/nodejs-api 

2) Tried creating a new workflow, using this existing workflow template to create a Docker image:

Docker image
By GitHub Actions

Build a Docker image to deploy, run, or push to a registry.
Docker image logo
docker build . --file Dockerfile --tag my-image-name:$(date +%s)


3) Set up Github Secrets for the variables GCP_EMAIL, GCP_CREDENTIALS, etc

4) Attempted to try Google Cloud Shell to run/deploy the project, but was unsuccessful.

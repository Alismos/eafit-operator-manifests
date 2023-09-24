# eafit-operator-manifests

## frontend-operator

### Build Dockerfile
docker build -t <\hub-user>/<\repo-name>:<\tag> -t <\hub-user>/<\repo-name>:<\tag>--no-cache .

### Run image
 
docker run -d -p 8080:80 -e BASE_URL="https://www.google.com" --name frontend-operator alismo1013/frontend-operator


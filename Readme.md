# Minio-Service
minio is one of the renowned object storages which is super easy to use and setup.

## Create Secret Username and Passwrod
To create secret username and password run the following command unless the default username=(minio12345) and password=(minio12345) will be set!

```commandline
MINIO_ROOT_USER=<your-secrete-user-name>
MINIO_ROOT_PASSWORD=<your-secrete-password>
```
**Note**: There should be no spaces between the variables and the values.

## Run
Run the following command to set up the minio and nginx
```commandline
docker-compose up --build
```
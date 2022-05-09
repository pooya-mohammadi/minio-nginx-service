# Minio-Service
minio is one of the renowned object storages which is super easy to use and setup.

## Create Secret Username and Password
To create secret username and password run the following command unless the default username=(minio12345) and password=(minio12345) will be set!

```commandline
export MINIO_ROOT_USER=<your-secrete-user-name>
export MINIO_ROOT_PASSWORD=<your-secrete-password>
```
**Note**: There should be no spaces between the variables and the values.
**NOTE**: Access key length should be at least 3, and secret key length at least 8 characters.
## Run
Run the following command to set up the minio and nginx
```commandline
docker-compose up --build
```

## Test
Browse to `localhost:9001/login` or `localhost:9000` to starting your amazing projects with minio-nginx

## References
1. https://github.com/minio/minio/tree/master/docs/orchestration/docker-compose
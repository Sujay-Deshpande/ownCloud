# ownCloud Using Docker

Create ```.env``` file for the specific repo (folder) and save the following data into ```.env``` file:

```sh
OWNCLOUD_VERSION=10.6
OWNCLOUD_DOMAIN=localhost:8080
OWNCLOUD_DOMAIN=""
ADMIN_USERNAME=#ChangeUserName
ADMIN_PASSWORD=#SetPassword
HTTP_PORT=8080
```

and run the docker Desktop in the system and run following command into the terminal of the vs code:

```sh
docker-compose up -d
```

and serch ``` http://localhost:8080 ``` on the browser. 

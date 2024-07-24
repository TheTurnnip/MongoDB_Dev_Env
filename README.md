# MongoDB_Dev_Env 

This is my personal docker compose file that I use for development with mongodb.

If you wish to use it, ensure that you change the credentials in the environment variables first
and I suggest against using mongo-express in any production environment.

The values to update are:
 - MONGO_INITDB_ROOT_USERNAME: This is the root user for the db.
 - MONGO_INITDB_ROOT_PASSWORD: This is the password for the root user of the db.
 - MONGO_INITDB_DATABASE: The name of the database to make the mongodb image with.
 - ME_CONFIG_BASICAUTH_USERNAME: The username for the webui.
 - ME_CONFIG_BASICAUTH_PASSWORD: The password for the webui.
 - ME_CONFIG_MONGODB_ADMINUSERNAME: The username for the root user of the db.
 - ME_CONFIG_MONGODB_ADMINPASSWORD: The password for the root user of the db.


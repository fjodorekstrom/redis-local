# Redis local
To run redis locally for products-service:

´´´
docker build . --tag redis
docker run -p 6379:6379 redis
´´´
If you want to expose another port on to which your server connects to the database you can change the ´-p´ values.

Then start your service that needs to connect to the redis session.

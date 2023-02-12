docker run --log-driver none -v db-data:/var/lib/postgresql/data -e POSTGRES_DB=wiki -e POSTGRES_PASSWORD=wikijsrocks -e POSTGRES_USER=wikijs postgres:11-alpine 
docker run -p 80:3000 -e DB_TYPE=postgres -e DB_HOST=db -e DB_PORT=5432 -e DB_USER=wikijs -e DB_PASS=wikijsrocks -e DB_NAME=wiki ghcr.io/requarks/wiki:2 

# User Login Code Challenge

This project uses [GoLang](https://go.dev/) to create backend API service to authenitcate users using a PostgreSQL database.

## How-To

1. Install [Go](https://go.dev/)
1. Install [Docker](https://docker.com/)
1. In the root folder of `scoir-back-end` execute the command `docker-compose up -d`, this will setup the database scoir_db.
1. In the root folder of `scoir-back-end` execute the command `go run ./cmd/api`, this will start the back-end service.
   API service will be located at [http://localhost:8080](http://localhost:8080).
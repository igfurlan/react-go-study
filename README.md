$ go mod init github.com/igfurlan/react-go-study

$ go get github.com/gofiber/fiber/v2

## Using AIR for automatic refresh
$ go install github.com/air-verse/air@latest
Create the air.toml file with the proper content

### Setup the .env
$ go get github.com/joho/godotenv
Create the .env file in the project folder


## Setup MongoDB
Access https://cloud.mongodb.com/ create an account. Create a new project, save the user and password. 
Save the connection string to the .env file

$ go get go.mongodb.org/mongo-driver/mongo

---

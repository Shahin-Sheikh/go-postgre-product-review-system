# go-postgre-product-review-system

## Step 1 – Setup the Golang Project

Run this command to initialize your project:

`go mod init github.com/Shahin-Sheikh/go-postgre-product-review-system`

We are going to use GORM for the ORM and postgre for the database.

Run this command to install GORM in your project:

`go get -u gorm.io/gorm`

Run this command to install postgres driver in your project:

`go get gorm.io/driver/postgres`

We are going to use Gin Gonic framework for creating the Golang server.

Run this command to install Gin Gonic framework in your project:

`go get github.com/gin-gonic/gin`

We are going to use Air package for live reload.

Run this command to install Air package in your project:

`go install github.com/cosmtrek/air@latest`

## Step 2 – Setup the Database

First create a app.env in your project, then enter your database credentials like below

POSTGRES_HOST=(IP address => 127.0.0.1)/localhost

POSTGRES_USER=username

POSTGRES_PASSWORD=db_password

POSTGRES_DB=db_name

POSTGRES_PORT=6500

PORT=8000

CLIENT_ORIGIN=http://localhost:3000

## Step 3 – Add .gitignore

To avoid accidental pushing of the environment variables to GitHub, create a `.gitignore` file and add the following code.

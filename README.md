# go-postgre-product-review-system

# Step 1 – Setup the Golang Project

1. Run this command to initialize your project

$ go mod init github.com/Shahin-Sheikh/go-postgre-product-review-system

We are going to use GORM for the ORM and postgre for the database.

2. Run this command to install GORM in your project

$ go get -u gorm.io/gorm

3. Run this command to install postgres driver in your project

$ go get gorm.io/driver/postgres

We are going to use Gin Gonic framework for creating the Golang server

4. Run this command to install Gin Gonic framework in your project

$ go get github.com/gin-gonic/gin

We are going to use Air package for live reload in every file change in the project

5. Run this command to install Air package

$ go install github.com/cosmtrek/air@latest

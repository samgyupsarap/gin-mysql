Install Gin
go get -u github.com/gin-gonic/gin


Connect Database
go get -u gorm.io/gorm 
go get -u gorm.io/driver/sqlite # For SQLite; use mysql or postgres for those databases
go get -u gorm.io/driver/mysql #for Mysql driver installation

Set env 
Example
DB_USER=yourusername 
DB_PASS=yourpassword 
DB_HOST=127.0.0.1:3306 
DB_NAME=yourdbname

gorm.io/gorm
The package gorm.io/gorm is the main library in Go's GORM (Go Object Relational Mapping) ecosystem, designed to simplify database interactions by providing an easy-to-use ORM framework for Go applications.

"github.com/joho/godotenv"
For importing env

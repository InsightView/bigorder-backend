# bigorder-backend

## init project 
```
go mod init
go mod test
go mod tidy
```

## build
```
go build -mod=readonly
# readonly cannot update dependency package 
go build -mod=vendor
```

## note
1. Using [official mongodb driver](https://github.com/mongodb/mongo-go-driver) cuz mgo is UNMAINTAINED.
2. 
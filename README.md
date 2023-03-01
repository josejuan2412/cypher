# Cypher

This program is a server that enables to encrypt and decrypt string

## Set key

1. Go to the file `server.go`
2. Modify line `15` to the value you want to set
3. Save the file

## Build the binary

### Linux
If you plan to run this for linux run the following command depending 
on the target architecture.

#### x64
`GOOS=linux GOARCH=amd64 go build server.go`

#### x32
`GOOS=linux GOARCH=386 go build server.go`

### Mac
If you plan to run this for mac run the following command depending 
on the target architecture.

#### x64
`GOOS=darwin GOARCH=amd64 go build server.go`

#### x32
`GOOS=darwin GOARCH=386 go build server.go`

### Windows
If you plan to run this for windows run the following command depending 
on the target architecture.

#### x64
`GOOS=windows GOARCH=amd64 go build server.go`

#### x32
`GOOS=windows GOARCH=386 go build server.go`
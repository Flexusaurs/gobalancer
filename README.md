# gobalancer

a simple load balancer written in Go, right now configured to use Round Robin for balancing connections.

# Usage
- first, run `go build main.go`

- set up some running endpoints, can be localhost with different ports

 - then run the executable with the following arguments as follows (localhost:port) :
` main.exe --backends=http://localhost:3031,http://localhost:3032,http://localhost:3033,http://localhost:3034`
---


# Future TODOS

- add docker configuration (Dockerfile, docker compose)
- other running configurations

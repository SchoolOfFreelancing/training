
all: build

build:
	CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build -o server .

docker:
	docker build -t appleboy/server .

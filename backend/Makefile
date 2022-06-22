.PHONY: build
build:
	mkdir -p bin
	go build -trimpath -o bin/server

.PHONY: run
run:
	go run main.go

.PHONY: dev
dev:
	go install github.com/pilu/fresh
	fresh

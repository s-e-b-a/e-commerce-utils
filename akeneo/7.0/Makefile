all: build push

default: build

build:
	docker build -f Dockerfile -t clickandmortar/akeneo:7.0 .

push:
	docker push clickandmortar/akeneo:7.0

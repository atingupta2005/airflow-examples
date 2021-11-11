build: build-base build-docker

build-base:
	docker build -t airfloweset/set12-base-image:latest -f Dockerfile.base .

build-docker:
	docker build -f Dockerfile.base .

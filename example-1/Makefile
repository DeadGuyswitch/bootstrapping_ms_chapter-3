build:
	docker build -t video-streaming --file Dockerfile .
run:
	docker run -d -p 3000:3000 video-streaming

tag:
	docker tag video-streaming nirdeshregistry.azurecr.io/video-streaming:latest
	
push:
	docker push nirdeshregistry.azurecr.io/video-streaming:latest
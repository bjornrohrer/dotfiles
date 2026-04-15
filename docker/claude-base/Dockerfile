FROM node:22-slim 

RUN apt-get update && apt-get install -y \ 
	git python3 python3-pip curl bash \
	&& rm -rf /var/lib/apt/lists/*
RUN npm install -g @anthropic-ai/claude-code

WORKDIR /project

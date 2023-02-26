FROM node:18.14.2-slim

ENV TZ Asia/Tokyo

WORKDIR /app

RUN apt-get update \
	&& apt-get install -y \
	git \
	vim

RUN npm install -D vuetify@next \
	mdi \
	sass \
	vite-plugin-vuetify

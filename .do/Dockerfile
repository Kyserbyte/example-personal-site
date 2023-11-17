FROM ghcr.io/peaceiris/hugo:latest-full

WORKDIR /app
COPY . /app

RUN npm install
RUN hugo -d public

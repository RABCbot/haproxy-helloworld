# haproxy-helloworld
Simple sample of haproxy config
Uses docker coopse file to simplify deployment

## Deploy
docker-compose up -d

## Test
http://<your-docker-ip>:8080
refresh page multiple times and see how round robin thru the three web pages


# docker-ghost

docker run -d --user="" -p 127.0.0.1:2368:2368 -v /data:/ghost --name www-website ghost npm start --production

docker run -d --user="" -p 127.0.0.1:2368:2368 -v /data:/ghost --name www-website ghost npm update

docker run -it -p 3000:3000 -v /home/node/app/node_modules -v $(pwd):/home/node/app jakecallery/frontend
docker build --no-cache -f Dockerfile.dev -t jakecallery/frontend --network=host .

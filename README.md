# goLightHTTP
dockerized light HTTP container, only 8.7Mb

Environment Variables:
 - SITE - the url to the static content to serve
 - DOMAIN - the domain that will server it up, mostly used in the stack deploy so traefik can route the stuff to it
 - IMAGE - the name of the image to build when you do `docker-compose build` and the name that the docker-stack.yaml will use if you use a stack deploy

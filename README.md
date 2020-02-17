# ModSecurity Docker Image

This is a docker images that creates a vhost configuration that includes a simple rule to test with
`curl localhost?attack=attack` and to test a specfic setup

Build
`sudo docker build -t ledzepp4eva/modsec:3.0.4 3.0.4/.`

Once built you can run this by running:
`sudo docker run -it -p 80:80 ledzepp4eva/modsec:3.0.4`

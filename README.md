# rails-on-docker

![](rails-on-docker.png)

Get Ruby on Rails working with passenger and on Docker in a few minutes.

## Usage

```bash
docker build --tag webapp .
docker run -p 80:80 -v $(pwd):/home/app/webapp webapp
docker-machine ip # note the ip address
```

Then visit the docker-machine ip address. That's it!



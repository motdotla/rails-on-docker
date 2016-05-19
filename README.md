# rails-on-docker

Get Ruby on Rails working with passenger and on Docker in a few minutes.

## Usage

```bash
docker build --tag webapp .
docker ps # note the container id of 'webapp' container
docker run -p 80:80 -d b6fe30ab582e # use container id of 'webapp'
docker-machine ip # note the ip address
```

Then visit the docker-machine ip address. That's it!



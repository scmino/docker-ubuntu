# docker-ubuntu

### Building an image (e.g. changing this one)
  Grab sources from Github
 - then rebuild:
```
docker build -t="scmino/ubuntu" .

# Interative: stop/delete/rebuild:
docker stop test && docker rm test && docker build -t="scmino/ubuntu" .
# Run and look at logs:
docker run -it --name test scmino/ubuntu
```


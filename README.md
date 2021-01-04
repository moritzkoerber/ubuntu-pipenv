# public built image at docker hub
at https://hub.docker.com/r/namgivu/ubuntu-pipenv

We aim to have the easy-to-use docker base-image in a Dockerfile
i.e. 
```dockerfile
FROM namgivu/ubuntu-pipenv:20.04-3.8
FROM namgivu/ubuntu-pipenv:18.04-3.7
FROM namgivu/ubuntu-pipenv:16.04-3.6
```

# target image name
namgivu/ubuntu-pipenv:UU-PP

UU = 16.04 or 18.04

PP = 3.6 or 3.7 or 3.8

```
python   ubuntu   image name                        Dockerfile                                docker hub url
------   ------   -------------------------------   ---------------------------------------   ----------------------------------------------
3.6      16.04    namgivu/ubuntu-pipenv:16.04-3.6   ./Dockerfile/vault/16.04-3.6.Dockerfile   https://hub.docker.com/r/namgivu/ubuntu-pipenv
3.6      18.04    namgivu/ubuntu-pipenv:18.04-3.6   ./Dockerfile/vault/18.04-3.6.Dockerfile   (as above)

3.7      16.04    namgivu/ubuntu-pipenv:16.04-3.7   ./Dockerfile/vault/16.04-3.7.Dockerfile   (as above) 
3.7      18.04    namgivu/ubuntu-pipenv:18.04-3.7   ./Dockerfile/vault/18.04-3.7.Dockerfile   (as above)

3.8      18.04    namgivu/ubuntu-pipenv:18.04-3.8   ./Dockerfile/vault/18.04-3.8.Dockerfile   (as above)
```


# info 0th
ubuntu with python docker image
ref. https://gist.github.com/monkut/c4c07059444fd06f3f8661e13ccac619

public built image at docker hub
at https://hub.docker.com/r/namgivu/ubuntu-pipenv


# what to run
view docstring in `./docker-build.sh`
view docstring in `./docker-image-push.sh`

# TODO 
TODO need test/docker-run.sh using the image

TODO need test/docker-compose.sh using the image

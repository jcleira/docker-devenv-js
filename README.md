# Dockerized JS development environment
![Docker JS environment](http://i.imgur.com/8PwCETt.png)

This repository contains my personal dockerized development environment for JS.

Usage:

```bash
docker run -t -i -v /home/<user>/.ssh:/home/dev/.ssh -v /home/<user>/.ssh:/home/dev/.ssh -v /home/<user>/Code:/home/dev/Code --net=host jcorral/docker-devenv-js
```

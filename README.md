<div align="center">

# SimpleWeb

*A simple dockerized website for testing servers.*

[![MIT License](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)](https://github.com/JoshuaTheMiller/SimpleWeb_StaticServer) 

[![Docker Build Status](https://img.shields.io/docker/build/trfc/simpleweb?style=flat-square)][docker] [![Docker Pulls](https://img.shields.io/docker/pulls/trfc/simpleweb?style=flat-square)][docker]

</div>

Once a container is running using this image, navigating to the exposed site should result in a page that looks like the following picture:

![example of the website](/example.PNG?raw=true "Example")

## Usage

```shell
# To run
sudo docker run --rm -p 80:80 -d -m 10m --name simpleweb trfc/simpleweb
# To stop/remove
sudo docker stop simpleweb
# To monitor
sudo docker stats simpleweb
```

 [docker]: https://hub.docker.com/repository/docker/trfc/simpleweb

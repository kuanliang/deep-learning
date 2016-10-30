# Deep learning environments for Docker
## Getting started
Pull docker image from [Docker Hub](https://hub.docker.com/r/yitabashi/deep-learning/).  
`$ docker pull yitabashi/deep-learning`  

Run image ***with [nvidia-docker](https://github.com/NVIDIA/nvidia-docker)***.  
`$ GPU=0 ./nvidia-docker run -itd -v $(pwd)/data:/root/data -p 6006:6006 --name deep yitabashi/deep-learning`  

## Special thanks
This project is based on https://github.com/ww24/docker-deep-learning.  
Thanks, ww24!


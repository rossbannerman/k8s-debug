# k8s-debug
Image with useful debug/testing tools pre-installed

## Image
[rossbannerman/k8s-debug](https://hub.docker.com/repository/docker/rossbannerman/k8s-debug)

## Usage
```bash
docker run --name k8s-debug --rm -it rossbannerman/k8s-debug /bin/bash
kubectl run --rm -i --tty debug --image=rossbannerman/k8s-debug -- /bin/bash
```

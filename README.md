# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/kubernetes-helm.tiller:${VERSION}
docker tag hawsers/kubernetes-helm.tiller:${VERSION} gcr.io/kubernetes-helm/tiller:${VERSION}
docker rmi hawsers/kubernetes-helm.tiller:${VERSION}
```

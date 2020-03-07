http://mirror.azure.cn/help/gcr-proxy-cache.html



GCR Proxy Cache服务器相当于一台GCR镜像服务器，国内用户可以经由该服务器从gcr.io下载镜像。


使用GCR Proxy Cache从gcr.io下载镜像

docker pull gcr.azk8s.cn/google_containers/<imagename>:<version>

例子

docker pull gcr.azk8s.cn/google_containers/pause-amd64:3.0

docker pull gcr.azk8s.cn/google_containers/kubedns-amd64:1.7

注意事项

从gcr.io下载镜像之前请确保已经安装了docker-engine。

来源

https://blog.docker.com/2015/10/registry-proxy-cache-docker-open-source/
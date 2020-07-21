## 直接设置 GO111MODULE=off

## github.com/docker/cli/cmd/docker 直接就可以跑

## program args: image ls


## curl -s --unix-socket /var/run/docker.sock http:/images/json

```.shell script

curl -s --unix-socket /var/run/docker.sock http:/containers/json
curl -s --unix-socket /var/run/docker.sock http:/images/json
```

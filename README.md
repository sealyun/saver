先：
```
docker run -it -w /etc/ansible -v /Users/fanux/work/src/github.com/sealyun/saver:/etc/ansible fanux/sealos:v1.13.2 ansible-playbook role/save-kube.yaml
```
然后到北京服务器上执行：
```
release-k8s.sh 1.13.2 香港服务器地址
```

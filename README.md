Usage: ./k8s-setup.sh $(your_server_ip)


setup kubernetes with one script. (author runs it on Ubuntu18.04)
make sure that:
 1. docker service installed. (check it with "systemctl status docker")
 2. etcd service installed. (check it with "etcdctl")
 3. cfssl installed. (check it with "cfssl")
 4. make a soft link to your kubernetes binaries at /opt/kubernetes/bin/ and /usr/bin/
 5. make a soft link to your etcd binaries at /opt/etcd/bin/ and /usr/bin/

docker-ubuntu-vnc-desktop
=========================

Copied from doruwu's repository and do some update based on personal requirement

[![Docker Pulls](https://img.shields.io/docker/pulls/castingnet/ubuntu-desktop-lxde-vnc.svg)](https://hub.docker.com/r/castingnet/ubuntu-desktop-lxde-vnc/)
[![Docker Stars](https://img.shields.io/docker/stars/castingnet/ubuntu-desktop-lxde-vnc.svg)](https://hub.docker.com/r/castingnet/ubuntu-desktop-lxde-vnc/)

From Docker Index
```
docker pull castingnet/ubuntu-desktop-lxde-vnc
```

Build yourself
```
git clone https://github.com/castingnet/docker-ubuntu-vnc-desktop.git
docker build --rm -t castingnet/ubuntu-desktop-lxde-vnc docker-ubuntu-vnc-desktop
```

Run
```
docker run -it --rm -p 6080:80 castingnet/ubuntu-desktop-lxde-vnc
```

Browse http://127.0.0.1:6080/

<img src="https://raw.github.com/castingnet/docker-ubuntu-vnc-desktop/master/screenshots/lxde.png" width=400/>


Troubleshooting
==================

1. boot2docker connection issue, https://github.com/castingnet/docker-ubuntu-vnc-desktop/issues/2


License
==================

See the LICENSE file for details.

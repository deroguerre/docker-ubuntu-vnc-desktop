browthergui
=========================

From Docker Index
```
docker pull dorowu/ubuntu-desktop-lxde-vnc
```

Build Dockerfile
```
docker build -t browthergui .
```

Run
```
docker run -d -i -t -p 6080:6080 -name browthergui dorowu/ubuntu-desktop-lxde-vnc
```

Browse http://127.0.0.1:6080/vnc.html

<img src="https://raw.github.com/fcwu/docker-ubuntu-vnc-desktop/master/screenshots/lxde.png" width=400/>


Troubleshooting
==================

1. boot2docker connection issue, https://github.com/fcwu/docker-ubuntu-vnc-desktop/issues/2


License
==================

desktop-mirror is under the Apache 2.0 license. See the LICENSE file for details.

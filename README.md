Browthergui
=========================

Build Dockerfile
```
docker build -t gui/browthergui .
```

Build yourself
```
git clone https://github.com/deroguerre/docker-ubuntu-vnc-desktop.git
docker build --rm -t gui/browthergui docker-ubuntu-vnc-desktop

Run
```
docker run -i -t -p 6080:6080 --name browthergui_container gui/browthergui
```

Browse http://127.0.0.1:6080/vnc.html

License
==================

desktop-mirror is under the Apache 2.0 license. See the LICENSE file for details.
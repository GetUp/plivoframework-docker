# getup/plivoframework-docker
Dockerized Plivoframework for developing Plivo apps locally

~~~bash
 docker run --privileged=true -p 5060:5060/tcp -p 5060:5060/udp -p 16384:16384/udp -p 16385:16385/udp -p 16386:16386/udp -p 16387:16387/udp -p 16388:16388/udp -p 16389:16389/udp -p 16390:16390/udp -p 16391:16391/udp -p 16392:16392/udp -p 16393:16393/udp -p 8088:8088 -p 5000:5000 -ti getup/plivoframework-docker
~~~

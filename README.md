# docker-apache-ignite
Lean (310MB) Apache Ignite docker image powered by Alpine.

[![Docker Repository on Quay](https://quay.io/repository/tpires/apache-ignite/status "Docker Repository on Quay")](https://quay.io/repository/tpires/apache-ignite)

## Software

* Apache Ignite 1.5.0.final
* Oracle JRE 8 Update 60

## Run

```
docker run --name ignite -d --net=host quay.io/tpires/docker-apache-ignite:1.5.0.final
```

Now, run:
```
$ docker logs -f ignite
Java HotSpot(TM) 64-Bit Server VM warning: ignoring option MaxPermSize=256m; support was removed in 8.0
[23:48:26]    __________  ________________ 
[23:48:26]   /  _/ ___/ |/ /  _/_  __/ __/ 
[23:48:26]  _/ // (7 7    // /  / / / _/   
[23:48:26] /___/\___/_/|_/___/ /_/ /___/  
[23:48:26] 
[23:48:26] ver. 1.5.0-final#20151229-sha1:f1f8cda2
[23:48:26] 2015 Copyright(C) Apache Software Foundation
[23:48:26] 
[23:48:26] Ignite documentation: http://ignite.apache.org
[23:48:26] 
[23:48:26] Quiet mode.
[23:48:26]   ^-- Logging to file '/ignite/work/log/ignite-2f424d22.0.log'
[23:48:26]   ^-- To see **FULL** console log here add -DIGNITE_QUIET=false or "-v" to ignite.{sh|bat}
[23:48:26] 
[23:48:26] OS: Linux 4.3.4-300.fc23.x86_64 amd64
[23:48:26] VM information: Java(TM) SE Runtime Environment 1.8.0_60-b27 Oracle Corporation Java HotSpot(TM) 64-Bit Server VM 25.60-b23
[23:48:26] Configured plugins:
[23:48:26]   ^-- None
[23:48:26] 
[23:48:27] Security status [authentication=off, tls/ssl=off]
[23:48:29] To start Console Management & Monitoring run ignitevisorcmd.{sh|bat}
[23:48:29] 
[23:48:29] Ignite node started OK (id=2f424d22)
[23:48:29] Topology snapshot [ver=1, servers=1, clients=0, CPUs=4, heap=1.0GB]

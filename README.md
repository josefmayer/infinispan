## Infinispan Cache
Basic Infinispan examples: Remote: <br />
Embedded, Distributed, Remote


### Technologies
Java, Cache, Infinispan, JGroups, HotRod <br />


### Modes
Embedded: <br />
Infinispan cache runs on same JVM as application <br />

Distributed: <br />
Caches form a cluster <br />

Remote: <br />
Server-client mode <br />
Infinispan cache runs it its own JVM <br />
Uses HotRot protocol <br />




### Steps
##### Embedded
*mvn clean compile exec:exec*<br />

##### Distributed
*mvn clean compile exec:exec*  <br />

##### Remote
Install Infinispan server
start Infinispan server: <br />
SERVER_HOME/bin/standalone.sh <br />

Run client:
*mvn clean compile exec:exec*  <br />



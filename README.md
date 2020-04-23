# TLB_2019

> 주요 명령어

zookeeper-server-start -daemon ./conf/zookeeper.properties

kafka-server-start -daemon ./conf/server.properties

ksql-server-start -daemon ./conf/ksql-server.properties

kafka-topics --create --topic twitter --zookeeper localhost:2181 --partitions 1 --replication-factor 1

kafka-console-producer --topic teste --broker-list localhost:9092

<br>

> jupyter lab 설치

pip3 install jupyterlab

jupyter lab --ip=* --no-browser

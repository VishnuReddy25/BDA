# BDA


http://tinyurl.com/bdaspark1

http://tinyurl.com/kafka5

https://tinyurl.com/kafkabda9


bin/kafka-server-start.sh config/server.properties
bin/zookeeper-server-start.sh config/zookeeper.properties

cd kafka_2.13 

GRAPHX

create new cluster (11.3)
go to compute -> go to your new cluster which has runtime 11.3 -> go to libraries
install new-> maven ->

cooedinates : graphframes:graphframes:0.8.2-spark3.1-s_2.12
respository : https://repo1.maven.org/maven2/

HIVE:
(base) hduser@system30-OptiPlex-3050:~$ sudo rm -Rf ~/metastore_db/
[sudo] password for hduser: 
(base) hduser@system30-OptiPlex-3050:~$ $HIVE_HOME/bin/schematool -initSchema -dbType derby 

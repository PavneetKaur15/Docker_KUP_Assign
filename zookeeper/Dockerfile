FROM openjdk:8-jre-slim

WORKDIR /kafka-dir

ADD kafka/ /kafka-dir/

CMD ./bin/zookeeper-server-start.sh config/zookeeper.properties


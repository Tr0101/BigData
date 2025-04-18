# BigData
Before starting coding, do these steps first to initialize the hadoop environment and create a data storage location on HDFS:
- Initialize the hadoop environment:
sudo service ssh start
hdfs namenode -format
start-all.sh
nmap -p 9000 localhost
nmap -p 8080 localhost
- Create a data storage location on HDFS:
hdfs dfs -mkdir -p /results
hdfs dfs -mkdir -p /data
hdfs dfs -chmod -R 777 /results
hdfs dfs -chmod -R 777 /data

实验五
jar包执行说明
1.启动Spark和yarn(使用spark其他运行模型则不需要, 修改--master后面的参数即可);
2.进入存放spark_itemset.jar的目录；
3.$SPARK_HOME/bin/spark-submit --master yarn --class FreItemSetMining spark_itemset.jar  hdfs://your/path/to/data.dat hdfs://your/output/path

注意:
1. /your/path/to/data.dat 为你的测试数据文件所在HDFS路径;
2. /your/output/path 为你的输出的文件HDFS路径；
3.$SPARK_HOME是你的spark安装目录;
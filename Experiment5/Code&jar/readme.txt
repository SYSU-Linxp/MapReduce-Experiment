ʵ����
jar��ִ��˵��
1.����Spark��yarn(ʹ��spark��������ģ������Ҫ, �޸�--master����Ĳ�������);
2.������spark_itemset.jar��Ŀ¼��
3.$SPARK_HOME/bin/spark-submit --master yarn --class FreItemSetMining spark_itemset.jar  hdfs://your/path/to/data.dat hdfs://your/output/path

ע��:
1. /your/path/to/data.dat Ϊ��Ĳ��������ļ�����HDFS·��;
2. /your/output/path Ϊ���������ļ�HDFS·����
3.$SPARK_HOME�����spark��װĿ¼;
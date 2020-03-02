# Spark Streaming实时流处理项目
这是一个spark流处理慕课网的课程日志项目,是一个上课笔记也是一个练手敲代码项目

流程图如下：
![架构图](C:\Users\ll\spark-streaming-project\structure.png)

本项目是实现了
1.数据采集（flume读取日志文件），
2.对接消息队列(kafka对接flume信息到spark streaming),
3.spark streaming处理数据流（进行数据清洗，简单的数据统计任务）
4.保存数据到hbase



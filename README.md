# CentOS8-ELK
CentOS8-ELK-Filebeat 集中式日志分析平台
# 技术栈
操作系统：CentOS 8

核心组件：Elasticsearch 7.14.0、Kibana 7.14.0、Logstash 7.14.0、Filebeat 7.14.0
# 系统架构
Filebeat：部署在本地，轻量级采集各类日志文件

Logstash：接收 beats 数据，过滤空日志、清洗格式化日志

Elasticsearch：分布式搜索引擎，存储日志数据

Kibana：可视化 Web 面板，日志查询、图表展示、故障排查

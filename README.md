# ahaha系列代码库 复刻一些好用的研发工具
phase1：搭建研发部门常见的基础架构工具：   
常用中间件接入（sentinel、redis、db、es、rocketmq）、中间件全链路、埋点监控、泳道、日志、配置后台、审核流后台、权限后台、ci/cd平台、网关、sso、定时任务后台、任务调度后台、自动化测试脚本后台、低代码网站平台、内网互联平台、mq管控平台、多az部署、断网演练、故障演练、资损核对平台、消息推送、hive开发平台、flink开发平台、流量录制/回放平台、压测、hive报表平台、隐私信息sidecar方案、数据库同步es/kafka/...、hive同步redis/es/kafka/clickhouse/hbase/...   

里程碑：
- 埋点/trace组件：opentelemetry + load balance + read/write proxy + prometheus/jaeger
参考资料：
https://cloud.tencent.com/developer/article/1950680
https://dbaplus.cn/news-134-4362-1.html
https://skywalking.apache.org/docs/#Agents
- 接入埋点，micrometer + prometheus


phase2：搭建一个电商系统：




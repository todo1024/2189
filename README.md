# 2189
尚硅谷Filebeat视频教程
### 微:NoBug1024 


课程介绍：

Filebeat 是使用 Golang 实现的轻量型日志采集器，也是 Elasticsearch stack 里面的一员。本质上是一个 agent ，可以安装在各个节点上，根据配置读取对应位置的日志，并上报到相应的地方去。

Filebeat 的可靠性很强，可以保证日志 At least once 的上报，同时也考虑了日志搜集中的各类问题，例如日志断点续读、文件名更改、日志 Truncated 等。

Filebeat 并不依赖于 ElasticSearch，可以单独存在。我们可以单独使用Filebeat进行日志的上报和搜集。filebeat 内置了常用的 Output 组件, 例如 kafka、ElasticSearch、redis 等，出于调试考虑，也可以输出到 console 和 file 。我们可以利用现有的 Output 组件，将日志进行上报。

当然，我们也可以自定义 Output 组件，让 Filebeat 将日志转发到我们想要的地方。

filebeat 其实是 elastic/beats 的一员，除了 filebeat 外，还有 HeartBeat、PacketBeat。这些 beat 的实现都是基于 libbeat 框架。


〖课程目录〗:

- ├──视频  
- |   ├──01_Filebeat课程介绍.mp4  7.92M
- |   ├──02_Filebeat的使用场景.mp4  14.84M
- |   ├──03_Filebeat和Logstash对比.mp4  13.56M
- |   ├──04_Filebeat的使用内容介绍.mp4  41.35M
- |   ├──05_Filebeat和logstash对接案例.mp4  71.84M
- |   ├──06_模块监控kafka功能介绍.mp4  46.50M
- |   ├──07_对接ES案例展示.mp4  48.91M
- |   ├──08_对接kafka案例展示.mp4  34.75M
- |   └──09_Filebeat框架总结.mp4  10.20M
- ├──笔记.zip  1.90M
- └──资料.zip  1.10G


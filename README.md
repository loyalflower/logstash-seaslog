# logstash-seaslog
针对PHP seaslog定制的logstash配置

由于seaslog官方并不支持直接输出json格式，而是以 | 分割字段形式的日志，因此也无法直接利用官方提供的csv格式。因此自己配置了一下。

## logstash 版本
logstash 5.3.0

## 支持的特性
1. 默认的seaslog日志
2. seaslog捕获的 php 异常

**暂时测试直接发送到elasticsearch**，但是我想应该不复杂

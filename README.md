# Flink Demo

参考 https://www.cnblogs.com/xiaodf/p/11757462.html 此文章写成

# 测试

## 模拟客户端

### Linux/macOS

```shell
nc -lk 9000
```

### Windows

先下载并安装 ncat https://nmap.org/ncat/

```shell
ncat -lk 9000
```

## 启动 flink-demo

运行服务，然后在模拟客户端的终端中数据单词，观察 flink-demo 的控制台
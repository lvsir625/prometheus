# prometheus
参考kubernetes官方的清单文件；
1:其中node-exporter是按照二进制部署的，使用k8s部署有问题
2:清单中持久存储有使用有的使用的静态创建pv，有的是动态创建pv（nfs存储类）
3：prometheus添加了对cpu，内存等报警的样例
4：alertmanager使用微信报警

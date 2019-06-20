# prometheus
参考kubernetes官方的清单文件；\n\n\n\n
1:其中node-exporter是按照二进制部署的，使用k8s部署有问题\n\n\n\n
2:清单中初九存储有使用有的使用的静态创建pv，有的是动态创建pv（nfs存储类）\n\n\n
3：prometheus添加了对cpu，内存等报警的样例\n\n
4：alertmanager使用微信报警\n

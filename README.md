# prometheus
参考kubernetes官方的清单文件；
1:其中node-exporter是按照二进制部署的，使用k8s部署有问题
2:清单中持久存储有使用有的使用的静态创建pv，有的是动态创建pv（前提是创建了nfs存储类），比如alertmanager的pv和pvc带有static的是静态创建，带有dynamics的是动态创建pv（县创建pvc，自动创建pv）
3：prometheus添加了对cpu，内存等报警的样例
4：alertmanager使用微信报警
5：kube-state-metrics-deployment中addon-resizer镜像可以使用googlecontainer/addon-resizer：1.8.4代替

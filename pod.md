# 什么是pod

一组，一个或多个容器构成



## 启动一个pod

```
[root@k8s-master01 ~]# kubectl run nginx-run --image=nginx:1.15.12
pod/nginx-run created
[root@k8s-master01 ~]# kubectl get po
NAME        READY   STATUS              RESTARTS   AGE
nginx-run   0/1     ContainerCreating   0          7s
[root@k8s-master01 ~]# kubectl get po
NAME        READY   STATUS              RESTARTS   AGE
```



基础设置即代码
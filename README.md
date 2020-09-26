# Kubernetes CRD示例

可以到我的个人主页上面查找文章[使用client-go访问k8s中的CRD](http://gzh.readthedocs.io)参考如何使用[k8s client-go](https://github.com/kubernetes/client-go)访问自定义CRD。

## 使用方法

安装：

```bash
go get github.com/double12gzh/k8s-demo
```

创建CRD:

```bash
kubectl apply -f https://raw.githubusercontent.com/double12gzh/k8s-demo/master/kubernetes/crd.yaml
kubectl apply -f https://raw.githubusercontent.com/double12gzh/k8s-demo/master/kubernetes/project.yaml
```
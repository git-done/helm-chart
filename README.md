# helm-chart

helm chart 仓库地址为: https://git-done.github.io/helm-chart

1、添加chart仓库

helm repo add myrepo  https://git-done.github.io/helm-chart

2、添加成功

helm repo list
myrepo         	https://git-done.github.io/helm-chart

3、搜索chart包

helm search repo myrepo/test
NAME       	CHART VERSION	APP VERSION	DESCRIPTION                
myrepo/test	0.1.0        	1.16.0     	A Helm chart for Kubernetes

4、安装chart 包

helm install xxx myrepo/test

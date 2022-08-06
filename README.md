# 权限控制

### &#x20;角色分类

* role：基于名称空间的角色，只能控制特定名称空间的资源
* clusterrole：基于集群的角色，可以控制整个集群的资源

> <mark style="color:red;">serviceaccout</mark> 相当于一个用户，他可以通过 **rolebinding** 来获取某些 **role** 或者 **clusterrole** 的权限,要想登录这个用户就可以使用它绑定的 **secret**&#x20;


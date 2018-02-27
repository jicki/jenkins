# Jenkins + jenkins slave

## 初始化init

```
sh init.sh

```


## docker and docker-compose

```

docker-compose up -d

```


## 配置 jenkins

```
1. 登录 web ui 

2. 系统管理 --> 管理节点 --> 新建节点 --> (不重复的名称，用于 JENKINS_AGENT_NAME )

3. 点击节点， 查看 节点 secret (用于 JENKINS_SECRET ) 

4. 等待 jenkins-jnlp 连接

5. 配置插件

6. 选择 自由风格 项目

```

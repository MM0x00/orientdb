# orientdb 在线实验环境

## 软件简介

OrientDB是第一个将图形的功能和文档的灵活性组合成一个可扩展的高性能操作数据库的多模型开源NoSQL DBMS

所属类别是数据库

特点：

灵活，并且结合图形容易观察，支持许多高级特性
## 软件官网

http://orientdb.com/orientdb/

## Dockerfile 使用方法

### 如何使用
当OrientDB启动时，它会询问root密码。root用户能够管理OrientDB服务器：创建新数据库，管理用户和角色。root密码可以使用环境属性传递给容器：
```
$ docker run -d --name orientdb -p 2424:2424 -p 2480:2480 -e ORIENTDB_ROOT_PASSWORD=rootpwd orientdb
```
该工作室可访问http：// <docker-host>：2480（例如：http：// localhost：2480）

## 资源链接

- http://orientdb.com/orientdb/
- https://hub.docker.com/_/orientdb/
- http://orientdb.com/docs/last/index.html

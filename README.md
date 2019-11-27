# 基于Beego的后台管理系统

## 后台模板：AdminLTE

### 使用步骤

1、先安装beego框架

2、获取项目
`$ go get github.com/huanzz/bgadmin`

3、新建mysql数据库

4、修改 conf/app.conf 中mysql的设置

5、终端下进入到项目目录
```
$ go build      
$ bgadmin syncdb   //数据库初始化
$ bee run
```

6、访问http://localhost:8080

## 效果展示
![](https://github.com/huanzz/beego__admin/blob/master/__images/1111111.png)
![](https://github.com/huanzz/beego__admin/blob/master/__images/222.png)
![](https://github.com/huanzz/beego__admin/blob/master/__images/333.png)
![](https://github.com/huanzz/beego__admin/blob/master/__images/444.png)
![](https://github.com/huanzz/beego__admin/blob/master/__images/55555555.png)
![](https://github.com/huanzz/beego__admin/blob/master/__images/666.png)


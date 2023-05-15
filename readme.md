# SVN - 版本控制

## ****SVN****

SVN的全称是subversion，SVN版本控制软件可以解决协助开发、远程开发和**版本回退**三个问题

特点：**操作简单、入门简单、跨平台操作**

SVN是输入C/S服务类软件，有客户端和服务端

## ****SVN的服务端****

1. checkout(检出)
2. update(更新)
3. Commit(提交、上传)


## ****SVN 使用的详解****

**三大指令**

- **checkout** 检出操作： 1.连接到服务器 2.第一次链接的时候更新数据到本地，后面使用update（更新指令）
- **commit** 提交代码：
    右键提交-->选择提交文件，写提交信息-->确定
    
    
- **update** 更新操作：右键更新操作即可自动更新最新的版本到本地

## ****图标集的含义****


1. 常规就是服务器和客户端数据一致
2. 无版本控制，编写好的文件没有上传队列
3. 锁定图标，服务器端已锁定

## ****忽略功能****

**忽略功能就是自己不想分享到服务器，仅仅是给自己看的内容：**

1. 忽略某个文件夹
    
   右键SVN-->增加到忽略列表-->选择文件
    
2. 忽略某个类型的文件
    
    右键SVN-->增加到忽略列表-->选择文件类型
    

## ****版本回退****

每次修改后，提交时写好备注，之后想回退版本，可以通过日志信息回退到想要的版本。
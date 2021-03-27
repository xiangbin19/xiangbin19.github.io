# 1day-1的笔记

# Linux初始化配置

+ 安装bash shell命令提示符

```
yum install -y bash-completion
```

+ 安装vim工具

```
yum install -y vim
```

+ 修改主机名称为server1

```
hostnamectl set-hostname server1
```

+ 关闭防火墙开机主动启动

```
systemctl disable firewalld
```

+ 关闭虚拟机

```
poweroff
```

+ 拍快照


---
title: "linux平台常用工具"
date: 2021-07-01T15:33:11+08:00
draft: false
---

# linux平台常用工具集

## 文件管理
- [ranger](https://github.com/ranger/ranger)
- 

## 进程管理

- [htop](https://htop.dev/) 比top更强大的Linux进程浏览器
- [mosh](https://mosh.org/)  轻量级 SSH 终端
- [Tmux](https://github.com/tmux/tmux) 窗口管理器
   
### docker 进程管理
1.  [ctop](https://ctop.sh/) 一个命令行的容器监视工具，可以动态的显示容器的cpu、内存、网络的使用情况
2. [ctop](https://github.com/yadutaf/ctop) 一款用python写的叫Ctop的工具 功能：
	- 收集cpu，pids，内存和块输入输出的度量值
	- 收集元数据，比如任务数，属主、容器技术等相关信息
	- 通过任意栏对信息排序
	- 按照容器类型进行筛选(docker, lxc, systemd, ...)
	- 以树状视图显示信息
	- 折叠/展开cgroup树
	- 选择并跟踪cgroup/容器
	- 选择显示数据刷新的时间窗口
	- 检测基于systemd、Docker和LXC的容器
	- 停止/杀死容器类型
1. [Seagull](https://github.com/tobegit3hub/seagull) 可以web管理和监控docker的工具
	- 可以非常容易的安装和卸载docker容器
	- 点击一下就可以开始/停止/删除容器和镜像
	- 可以在10ms以内快速搜索和筛选
	- 支持多主机管理和监控


## 高级日志文件查看器
- [lnav](https://lnav.org/)
- [logviewer](http://www.uvviewsoft.com/logviewer/) 一款比较轻量型的日志查看工具，它能够处理4G以上的日志文件

## 监控
1. [pyDash](https://github.com/dgilland/pydash) 基于pydash临控linux服务器

## 环境管理
- [asdf](https://asdf-vm.com) 管理Node.js, Ruby, Python多版本
- [jenv](https://www.jenv.be/) 管理多jdk版本
- [penv](https://pypi.org/project/penv/) 管理多python版本

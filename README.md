<h3 align="center">OneOps-Deploy</h3>
<p align="center">
  <a href="https://github.com/veops/OneOps-deploy/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-AGPLv3-brightgreen" alt="License: GPLv3"></a>
  <a href="https://goreportcard.com/report/github.com/veops/messenger"><img src="https://goreportcard.com/badge/github.com/veops/messenger" alt="API"></a>
</p>

**OneOps-Deploy**是一个运维产品集合，支持使用Docker Compose一键部署所有服务。目前包含**CMDB**, **OneTerm**, **ACL**, 未来会加入其他一些运维产品。

---

[English](README_en.md) / [中文](README.md)

- 产品文档：https://veops.cn/docs/
- 在线体验: <a href="https://term.veops.cn" target="_blank">OneOps</a>
    - username: **`demo`**   或者   **`admin`**
    - password: **`123456`**
> **重要提示**: 体验账号是多人共享，因此后台数据会不定期重置

## 项目模块

- [CMDB](https://github.com/veops/cmdb) 资产配置管理系统
- [OneTerm](https://github.com/veops/oneterm) 堡垒机
- [ACL](https://github.com/veops/acl) 权限管理系统(在OneOps-Deploy项目中已经内置于CMDB)

## 安装

### Docker 一键快速构建
- 第一步: 先安装 Docker 环境, 以及Docker Compose (v2)
- 第二步: 拷贝项目
```shell 
git clone https://github.com/veops/OneOps-deploy.git
```
- 第三步：进入主目录，执行:
```
docker compose up -d
```

## 验证
### 浏览器
- 地址: [http://127.0.0.1:8080](http://127.0.0.1:8080)
- username: admin
- password: 123456
### 终端
```shell
ssh -p 12230 admin@127.0.0.1
```

## 更多文档
- [安装及使用文档](https://veops.cn/docs/)

## 其他
> 目前一键部署上某些配置使用的是默认的一些账号密码，生产上建议修改相关配置值


![Wechat Official Account: 维易科技OneOps](docs/images/wechat.png)



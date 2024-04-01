<h3 align="center">OneOps-Deploy</h3>
<p align="center">
  <a href="https://github.com/veops/OneOps-deploy/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-AGPLv3-brightgreen" alt="License: GPLv3"></a>
  <a href="https://goreportcard.com/report/github.com/veops/messenger"><img src="https://goreportcard.com/badge/github.com/veops/messenger" alt="API"></a>
</p>
OneOps-Deploy is a one-click deployment service within the collection of operations and maintenance products, supporting the one-click deployment of all services using Docker Compose. It currently includes CMDB, OneTerm, ACL, and will incorporate additional operations and maintenance products in the future.

---

[English](README_en.md) / [中文](README.md)

- Product document：https://veops.cn/docs/
- Preview online: <a href="https://term.veops.cn" target="_blank">OneOps</a>
    - username: **`demo`**   or   **`admin`**
    - password: 123456

> **ATTENTION**: The experience account is shared among multiple users, therefore the backend data will be reset periodically.

## Modules

- [CMDB](https://github.com/veops/cmdb) Configuration Management Database
- [OneTerm](https://github.com/veops/oneterm) Jump Server Or Bastion Host
- [ACL](https://github.com/veops/acl) Access Control System (already integrated into CMDB within the OneOps-Deploy project)


## Installation

### Docker 
- Step 1: Install the Docker environment and Docker Compose (v2)
- Step 2: Copy the project
```shell 
git clone https://github.com/veops/OneOps-deploy.git
```
- Step 3: Enter the main directory and execute:
```
docker compose up -d
```

## Verification
### Browser
- Address: [http://127.0.0.1:8080](http://127.0.0.1:8080)
- username: admin
- password: 123456
### Terminal
```shell
ssh -p 12230 admin@127.0.0.1
```

## More Documentation
- [Installation and Usage Documentation](https://veops.cn/docs/)

## Others
> Currently, some configurations in the one-click deployment use default usernames and passwords, it is recommended to modify related configuration values in production environments.


![Wechat Official Account: 维易科技OneOps](backend/docs/images/wechat.jpg)

![Wechat Official Account: 维易科技OneOps](docs/images/wechat.png)

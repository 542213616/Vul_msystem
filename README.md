<<<<<<< HEAD
<<<<<<< HEAD


主要由3部分组成：
* 应用系统资产管理
* 漏洞生命周期管理
* 安全知识库管理

应用系统资产管理：对公司应用系统资产进行管理，包括系统名称、域名、重要级别、部门、负责人等。

漏洞生命周期管理：对公司应用系统产生的安全漏洞进行线上提交、通告、知悉、复测、分类、风险计算、修复期限计算、邮件提醒、漏洞数据分析统计等。

安全知识库管理：对安全知识、管理制度进行集中存放、线上学习、安全培训、知识传承等。


## 部署指南

[![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)](https://www.python.org/)
[![MySQL 5.7.13](https://img.shields.io/badge/mysql-5.7.13-orange.svg)](https://www.mysql.com)
[![Flask 0.11.1](https://img.shields.io/badge/flask-0.11.1-yellow.svg)](https://github.com/pallets/flask)
[![Docker 1.13.0](https://img.shields.io/badge/docker-1.13.0-blue.svg)](https://www.docker.com/)

目前只编写了docker部署指南，建议docker部署，详细请见：

[docker部署指南](docs/install.md)

## 使用指南

平台用户分为以下5种角色：
* 匿名用户：公司内部未登录用户
* 普通用户：普通登录用户，指公司研发、业务、产品经理等。
* 安全人员：安全部门进行漏洞测试、提交、跟踪修复的人员等。
* 安全管理员：安全部门对漏洞进行审核的管理人员。
* 超级管理员：最高权限账号，对用户的角色进行分配。

以上5种角色对应的使用文档请见：

[使用指南-匿名用户篇](docs/anonymous_user.md)

[使用指南-普通用户篇](docs/normal_user.md)

[使用指南-安全人员篇](docs/sec_user.md)

[使用指南-安全管理员篇](docs/sec_manager.md)

[使用指南-超级管理员篇](docs/super_user.md)



# 医院管理系统 python481

本项目是一个基于Python和Django框架开发的医院管理系统，配有详细的使用文档。系统主要涵盖患者、医生和管理员三种角色，提供了一套全面且实用的功能模块。

## 技术栈

- 后端：Python 3.x
- Web框架：Django
- 数据库：PostgreSQL（或其他Django支持的数据库）
- 前端：HTML, CSS, JavaScript

## 功能模块

### 管理员

- 科室管理：查看科室列表，展示department表中的内容。
- 医生管理：查看医生列表，添加新医生（需填写科室编号）。
- 药品管理：查看药品列表，添加新药品。
- 患者管理：查看患者列表，添加新患者（即患者注册）。

### 医生

- 接诊房间：查看待诊列表，仅限于医生所属科室的患者。
- 完成就诊：输入医嘱，开药。
- 就诊记录：查看历史就诊记录和药品清单。

## 系统角色

- 患者：注册信息，接受诊疗。
- 医生：接诊患者，记录诊疗过程，开立处方。
- 管理员：维护系统，管理科室、医生和药品信息。

## 运行环境

- 操作系统：支持Django的操作系统，如Linux、macOS或Windows。
- Python环境：Python 3.x
- 数据库：需安装PostgreSQL或其他Django支持的数据库。

## 部署步骤

1. 环境准备：安装Python 3.x和数据库。
2. 克隆代码仓库：`git clone [仓库地址]`
3. 安装依赖：`pip install -r requirements.txt`
4. 数据库迁移：`python manage.py makemigrations` 和 `python manage.py migrate`
5. 运行开发服务器：`python manage.py runserver`

## 目录结构

```
hospital_management_system/
├── apps/
│   ├── patients/
│   ├── doctors/
│   └── admin/
├── db/
├── media/
├── static/
├── templates/
├── manage.py
└── ...
```

## 核心亮点

- 多角色支持：患者、医生和管理员各司其职，分工明确。
- 功能全面：涵盖医院管理的各个方面，包括科室、医生、患者和药品管理。
- 易于维护：基于Django，遵循MVC设计模式，代码结构清晰。
- 详细的文档：配有全面的使用手册，方便用户和开发者理解和操作。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img14.360buyimg.com/ddimg/jfs/t1/334606/25/17077/5972/68d4dc49F12d0aed6/3a638d34e9e065bc.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/308377/14/22923/13177/68d4dc49Ffe70bd2e/aa5b75e768fab2ef.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/238535/13/30729/10732/68d4dc4aF29c992a7/91a73a28fd3aee96.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/329954/39/17245/12082/68d4dc4aF20095fec/edc7aab40f0b1f53.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/339694/34/14723/16108/68d4dc4aF384bfac6/fdc974e65846ab11.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/348039/39/7121/46515/68d4dc4bFbdf0dbc7/5de41cf2a584b3f1.jpg)

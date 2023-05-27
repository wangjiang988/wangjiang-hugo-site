---
layout:     post
title:      "基础平台微服务设计和开发"
subtitle:   "基于foundation框架的微服务设计，基础平台微服务设计和开发，版本迭代文档"
description: "foundation框架的参数化设计,修改历史..."
date:    2023-01-07
author:     "王将"
image: "/img/istio-install_and_example/post-bg.jpg"
tags:
    - microservice
    - work
    - platform
URL: "/2023/01/28/microservice-platform-design/"
categories: [ Microservice ]
---

## 微服务功能说明

平台的基础服务，包括用户管理，系统管理，用户权限设置等

## 版本迭代


### 系统管理

1. 系统配置
2. 数据字典
3. 系统日志
    登录日志
    操作日志

### 基础配置

1. 菜单管理
2. 组织架构
3. 用户管理
4. 用户组管理
5. 角色管理


### 代码自动生成

> 前端

    routes.ts 添加路由(参数：路由，对应page的路径)
    pages 生成路由文件
    https 生成api请求文件
    view 对象属性
    constant 修改cloumns 字段,修改按钮权限
    

### 1.0.0

基于foundation 框架 1.0.1-snapshot开发

集成功能：  
   
    1. swagger http://localhost:8080/swagger-ui/index.html
    2. flyway
    3. jwt (自动登录走/login，username,password登录)

用户管理
    curd
    导入导出


项目管理

代码路径: https://gitee.com/yuanhe-wuji/foundation-platform-v2.git
项目文档： https://e.gitee.com/yuanhe-wuji/projects/486906/tasks/table
知识库： https://e.gitee.com/yuanhe-wuji/projects/486906/docs?directory=0&page=1&program_id=0&scope=root




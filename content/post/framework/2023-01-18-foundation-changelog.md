---
layout:     post
title:      "foundation-framework"
subtitle:   "foundation框架的设计和修改历史"
description: "foundation框架的参数化设计, 如接口请求时，如何自动解析参数，定义参数规则等..."
date:    2023-01-07
author:     "王将"
image: "/img/istio-install_and_example/post-bg.jpg"
tags:
    - foundation
    - work
    - framework
URL: "/2023/01/07/foundation-params-parse-design/"
categories: [ Framework ]
---



## 主要模块

### 1.0.0

1. 授权模块（oauth2.0）  
    a. 支持oauth2.0，自定义资源数据库

2. mdc模块  
    traceId跟踪

3. flyway模块  
    数据库版本管理

4. k8s-config模块  
    k8s统一配置（config-map）

5. metrics模块  
    指标

6. jwt模块  
    jwt 登录(非oauth2.0接入方式) 测试是foundation-test

7. foundation-mybatis-domain-starter  （foundation-mybatis-starter弃用）  
    domain-starter mybatis 接入


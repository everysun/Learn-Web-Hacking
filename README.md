# Web安全学习笔记

一些常见的Web安全相关知识，来自于本人学习过程中做的总结，尚有缺漏或未完成的部分，持续更新中，如有错误请不吝指出。在线版本可点击[此处](https://websec.readthedocs.io)查看。

在完成的过程中参考了一些blog，皆在文末给出相应链接，感谢blog作者的分享。

该仓库仅供学习和交流使用，请勿使用相关内容进行非法行为。

### 目录结构

1. 基础知识
    - Web发展简史
    - 计算机网络
    - 域名系统
    - HTTP标准
    - 审计流程大纲
    - 内网渗透
    - 防御思路
2. 信息收集
    - 域名信息收集
    - 站点信息收集
    - 端口信息
    - Linux 本地信息收集
    - 其它
3. 常见漏洞
    - SQL注入
    - XSS
    - 文件相关漏洞
    - XXE
    - CSRF
    - SSRF
    - 模版注入
    - Xpath注入
    - 命令注入
    - 逻辑漏洞 / 业务漏洞
    - 配置安全
    - 引擎解析漏洞
    - Web Cache欺骗攻击
4. 语言及其框架相关漏洞
    - PHP相关漏洞
    - Python相关漏洞
    - Java
    - JavaScript
5. 工具与资源
    - 爆破工具
    - 下载工具
    - 流量相关
    - 嗅探工具
    - SQLMap使用
    - 工具列表
    - 推荐资源
6. 其他
    - 认证方式
    - 拒绝服务攻击
    - Docker安全
    - 应急响应
    - 溯源分析

### 生成 HTML 格式的文档

```shell
$ sudo pip install sphinx
$ sudo pip install sphinx-rtd-theme
$ make html
```

### 反馈

欢迎大家提出各种意见和建议，不胜感激。

反馈邮箱 ``lylemi@126.com``

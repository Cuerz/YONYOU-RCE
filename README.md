# 用友NC 漏洞合集
# CNVD-2021-30167

## FOFA

```
title="YONYOU NC"
icon_hash="1085941792"
```

## 使用方法

```
python ./xx.py -u http://www.example.com --check
python ./xx.py -u http://www.example.com --cmd "whoami"
python ./xx.py -f target.txt

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     Start scanning url
  -f FILE, --file FILE  read the url from the file
  --check               Check if vulnerable
  --cmd CMD             execute cmd (i.e: "ls -l")
```


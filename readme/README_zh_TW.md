# xy_file

- zh_CN [简体中文](README_zh_CN.md)
- zh_TW [繁体中文](README_zh_TW.md)
- en [English](README_en.md)


## 說明
簡單檔操作工具，特殊功能為不同路徑匹配規則的添加。

<a href="https://github.com/ShipOfOcean/xy_file.git" target="_blank">Github位址</a>

## 安裝

```bash
pip install xy_file
```

## 使用

###### 1. 命令行
```bash
# 刪除目前的目錄下所有 py 文稿檔
xy_file -w clean -g "*.py"

```

###### 2. python腳本

```python
from xy_file.File import File
from pathlib import Path

touch_file_path = Path.cwd().joinpath("test.txt")
# 創建檔案當該檔案路徑為空
file_path = File.touch(touch_file_path)
# 如果file_path不為空 說明創建空檔成功
```

## 捐贈

如果小夥伴們覺得這些工具還不錯的話，能否請咱喝一杯咖啡呢
<br />
![微信](WeChat.png)
![支付寶](Alipay.png)


## 聯繫方式



```
微信: yuyangitt
郵箱: 845262968@qq.com
```
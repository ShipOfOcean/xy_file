# xy_file

- zh_CN [简体中文](README_zh_CN.md)
- zh_TW [繁体中文](README_zh_TW.md)
- en [English](README_en.md)


## Description
Easy File tools, especially for regular.

<a href="https://github.com/ShipOfOcean/xy_file.git" target="_blank">Github</a>

## 安装

```bash
pip install xy_file
```

## How to use

###### 1. Terminal
```bash
# Delete all py files under current work folder.
xy_file -w clean -g "*.py"

```

###### 2. python script

```python
from xy_file.File import File
from pathlib import Path

touch_file_path = Path.cwd().joinpath("test.txt")
# create file if it not exists
file_path = File.touch(touch_file_path)
# if file_path is not empty, it means you created the file successful.
```

## Donate

If you think these tools are pretty good, Can you please have a cup of coffee?
<br/>
![WeChat](WeChat.png)
![Alipay](Alipay.png)

## Contact


```
Wechat: yuyangitt
Mail: 845262968@qq.com
```
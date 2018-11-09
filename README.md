## simple sign in

[![Build Status](https://travis-ci.org/tracyone/simpleSignin.svg?branch=unicomapp)](https://travis-ci.org/tracyone/simpleSignin)

简单的自动签到，通常用于可以根据用户名和密码就可以进行登录和签到的场景，便于自动化，涉及js加载校验和验证码识别的，可另寻其他方法。

自动化的签到是利用travis-ci完成的，这种方式不需要单独购买vps维护。

## Usage

* fork this project

* 注册travis-ci, 然后加入project

* 设置环境变量和运行计划


![](travis-ci.png)

本地运行:

1. 安装依赖

```
sudo pip3 install selenium requestium pyquery
```

2. export环境变量

```
export unicomapp_username="18382289346"
export unicomapp_password="123456"
```

3. 运行仓库下面的python脚本

```
whereis google-chrome-stable
python3 ci-test.py
```

## support

* unicom app(中国联通手机营业厅)

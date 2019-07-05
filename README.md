# English introduction

## ipv6-host

Using this host file, you can access to google, google scholar, google translation, google driver, youtube, facebook in China domain.

The videos on Youtube are now available.
## How to do?

Replace the **hosts** file in specific folder with the **hosts** file in the github.

That's all, and enjoy Google in ipv6.

## Where is the hosts?

System| path
--|--
Windows| C:\Windows\System32\drivers\etc\hosts
Macbook| /etc/hosts
Ubuntu|  /etc/hosts

## The accessible website

* Google
* Google scholar
* Gmail
* Google docs
* Google driver
* Google Translate
* youtube
* facebook
* Wikipedia zh
* Wikipedia en

## Still Not accessible to google after changing the hosts and obtaining IPv6 address

1. reboot your computer
2. reboot your router
3. type `tracert www.google.com` on the command line

### How to use Command Line 

System| How
--|--
Windows| win+R, type `cmd` in the input block, push button `Enter`
Macbook| search for `terminal`
Ubuntu| ctrl + t or search for `terminal`

* How to do in Windows, similar in Macbook or Ubuntu

```python
C:\Users\lijy2>tracert www.google.com

通过最多 30 个跃点跟踪
到 www.google.com [2404:6800:4005:808::2004] 的路由:

  1    <1 毫秒   <1 毫秒   <1 毫秒 4006:e024:680:95ac::1
  2     1 ms     1 ms     1 ms  cernet.edu.cn [2001:250:3002:4410::1]
  3     1 ms     1 ms     1 ms  fd44:2241::ff01
  4    <1 毫秒   <1 毫秒   <1 毫秒 fd44:1022::ff01
  5     1 ms     1 ms     1 ms  fd04:110::ff01
  6     5 ms     2 ms     2 ms  fd00:110::ff02
  7     6 ms     5 ms     3 ms  cernet2.net [2001:da8:a2:102::1]
  8     3 ms     2 ms     2 ms  2001:da8:2:104::1
  9    18 ms    12 ms    14 ms  2001:da8:2:16::2
 10    32 ms    32 ms    32 ms  2001:da8:2:f::1
 11    28 ms    27 ms    34 ms  2001:da8:2:d::2
 12    39 ms    35 ms    36 ms  2001:da8:2:1::1
 13     *        *        *     请求超时。
 14    46 ms    42 ms    42 ms  cernet2.net [2001:252:0:100::2]
 15    73 ms     *       73 ms  cernet2.net [2001:252:0:103::2]
 16    80 ms    81 ms    77 ms  google2-lacp-100g.hkix.net [2001:7fa:0:1::ca28:a10a]
 17    78 ms    79 ms    81 ms  2001:4860:0:e07::1
 18    80 ms    75 ms  2890 ms  2001:4860:0:1::825
 19   202 ms   103 ms    89 ms  ggpht.com [2404:6800:4005:808::2004]

跟踪完成。

C:\Users\lijy2>
```

# 中文版介绍

## ivp6-host
使用这个host file, 你就可以在中国大陆境内通过ipv6来访问谷歌，谷歌学术，谷歌翻译，谷歌驱动，youtube，脸书等。
**目前youtube的视频也可以看了**

## 怎么做？

将这个repo中的hosts文件，替换掉在自己电脑的特定目录下的hosts文件就好了。

就是这么简单，享受ipv6。

## hosts文件究竟在哪？

系统| 文件目录
--|--
Windows| C:\Windows\System32\drivers\etc\hosts
Macbook| /etc/hosts
Ubuntu|  /etc/hosts


## 可以访问的网站

* 谷歌
* 谷歌学术
* Gmail
* 谷歌文档
* 谷歌驱动
* 谷歌翻译
* Youtube
* 脸书
* 中文维基百科
* 英文维基百科


## 当有IPv6地址且修改Hosts文件但却没办法访问上述网站时的解决方案

1. 重启电脑
2. 重启路由器
3. 在命令行下输入，`tracert www.google.com`

### 关于命令行如何打开

系统| 如何打开
--|--
Windows| win+R，在运行框下输入`cmd`，回车
Macbook| 搜索terminal
Ubuntu| ctrl + t 或者搜索terminal


* windows效果如下

```python
C:\Users\lijy2>tracert www.google.com

通过最多 30 个跃点跟踪
到 www.google.com [2404:6800:4005:808::2004] 的路由:

  1    <1 毫秒   <1 毫秒   <1 毫秒 4006:e024:680:95ac::1
  2     1 ms     1 ms     1 ms  cernet.edu.cn [2001:250:3002:4410::1]
  3     1 ms     1 ms     1 ms  fd44:2241::ff01
  4    <1 毫秒   <1 毫秒   <1 毫秒 fd44:1022::ff01
  5     1 ms     1 ms     1 ms  fd04:110::ff01
  6     5 ms     2 ms     2 ms  fd00:110::ff02
  7     6 ms     5 ms     3 ms  cernet2.net [2001:da8:a2:102::1]
  8     3 ms     2 ms     2 ms  2001:da8:2:104::1
  9    18 ms    12 ms    14 ms  2001:da8:2:16::2
 10    32 ms    32 ms    32 ms  2001:da8:2:f::1
 11    28 ms    27 ms    34 ms  2001:da8:2:d::2
 12    39 ms    35 ms    36 ms  2001:da8:2:1::1
 13     *        *        *     请求超时。
 14    46 ms    42 ms    42 ms  cernet2.net [2001:252:0:100::2]
 15    73 ms     *       73 ms  cernet2.net [2001:252:0:103::2]
 16    80 ms    81 ms    77 ms  google2-lacp-100g.hkix.net [2001:7fa:0:1::ca28:a10a]
 17    78 ms    79 ms    81 ms  2001:4860:0:e07::1
 18    80 ms    75 ms  2890 ms  2001:4860:0:1::825
 19   202 ms   103 ms    89 ms  ggpht.com [2404:6800:4005:808::2004]

跟踪完成。

C:\Users\lijy2>
```
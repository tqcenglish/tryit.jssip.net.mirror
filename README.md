# tryit.jssip.net.mirror
MIRROR of tryit.jssip.net

## 克隆网站

```
wget --mirror -p --convert-links -P [本地目錄] [網站地址]

參數講解：
--mirror：設置這個參數用來建立本地鏡像
-p：下載所有HTML適合顯示的元素
--convert-links：將所有鏈接轉為本地鏈接
-P [本地目錄]：儲存文件到本地目錄下
```

在 [https://tryit.jssip.net/js/](https://tryit.jssip.net/js/) 中用详细的 custom 说明。
**音频文件** 需要手动下载
## 修改

针对镜像做如下修改

* 界面默认关闭视频接收
* 呼叫默认取消 enable_video
* 接听时默认取消视频
* 默认关闭session_timers
* 默认开启hack_ip_in_contact

##使用方法

[在线访问](https://tqcenglish.github.io/tryit.jssip.net.mirror)

以在192.168.1.25上的分机680为例,需要如下图填写后**回车**登陆:

![](https://raw.githubusercontent.com/tqcenglish/tryit.jssip.net.mirror/master/example1.png)

##注意

* 确保分机正确配置
* 确保端口和地址正确
* Chrome浏览器在开启VPN时不能正确接受数据包,导致无声音
* 电脑设置有多个 IP 地址
* NAT是否正确设置
* FireFox 39 版本与Asterisk(2015年 08月 05日 星期三 14:17:54 CST )[不兼容](https://issues.asterisk.org/jira/browse/ASTERISK-25265), FireFox 必须要可信任的证书, Chrome 可以使用不可信任的证书。
* FireFox Hold失败
* 必须运行在 https 下。

https://tqcenglish.github.io/tryit.jssip.net.mirror/tryit.jssip.net/
https://tryit.jssip.net/#

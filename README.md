# ukylin wine for Ubuntu

## 软件说明
> 本项目灵感来自ubuntu ukylin的自带wine项目,但是ubuntu ukylin我用的不是很舒服,而且现在ubuntu ukylin20.04也不自带这些软件包，且软件商店不可下载，本项目优势为wine运行的软件不需解决字体，图片，以及文件选择问题。

## 一、项目介绍
> ukylin-wine 环境的 Ubuntu 可安装版本

> 仅在ubuntu20.04和ubuntu16.04上测试过，不保证在其他系统上可用

## 二、使用介绍
> 下载ukylin wine到本地

[点击下载ukylin-wine](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/ukylin-wine_70.6.3.25_amd64.deb)
> 安装ukylin wine
```
sudo dpkg -i ./ukylin-wine_70.6.3.25_amd64.deb
```
> 接下来可以在release页面下载想要使用的应用,使用sudo dpkg -i ./安装包文件名 安装拉～

## 三、Release页面软件下载链接
1. [360压缩](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/360zip_1.0.0.1010_amd64.deb)
2. [百度网盘](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/baidunetdisk_3.5.0_amd64.deb)
3. [360浏览器(真的有人会用吗？)](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/browser360-cn-stable_12.2.1070.0-1_amd64.deb)
4. [飞书](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/bytedance-feishu-stable_4.8.0-52_amd64.deb)
5. [蓝信+](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/cn.lanxin_7.9.14.600772_amd64.deb)
6. [迅雷下载](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/com.xunlei.download_1.0.0.1_amd64.deb)
7. [点聚阅读器](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/dianjureader_20.0916-3.0_amd64.deb)
8. [奇安信可信浏览器](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/qaxbrowser-safe-stable_1.0.1969.2-1_amd64.deb)
9. [QQ音乐](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/qqmusic_1.0.8_amd64.deb)
10. [腾讯视频](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/tenvideo-universal_1.0.10_amd64.deb)
11. [QQ](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/ukylin-qq_1.0_amd64.deb)
12. [腾讯会议](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/ukylin-TencentMeeting_1.0_amd64.deb)
13. [微信](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/ukylin-wechat_3.0.0_amd64.deb)
14. [企业微信](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/wxwork_1.0_amd64.deb)
15. [有到词典](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/youdao-dict_6.0.0-0.ubuntu_amd64.deb)
16. [优酷](https://github.com/duanzhichao/ukylin-wine-ubuntu/releases/download/%E8%BD%AF%E4%BB%B6/youku-app_1.0.0_amd64.deb)

## 四、常见问题
1. ubuntu20.04托盘问题
> 安装TopIcons Plus, 重启

  [TopIcons Plus](https://extensions.gnome.org/extension/1031/topicons/)
```
sudo apt install gnome-tweak-tool gnome-shell-extension-top-icons-plus
```
2. ubuntu16.04下无法使用托盘问题
> 安装indicator-systemtray-unity,重启即可
```
sudo apt-add-repository ppa:fixnix/indicator-systemtray-unity
sudo apt-get update
sudo apt-get install indicator-systemtray-unity
```
3. 设置高分屏缩放
```shell
env WINEPREFIX="$HOME/.ukylin-wine/wechat" /usr/bin/ukylin-wine winecfg
```

## 五、感谢
[wszqkzqk/deepin-wine-ubuntu](https://github.com/wszqkzqk/deepin-wine-ubuntu/)

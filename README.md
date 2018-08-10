# Flutter-Learning

# 环境搭建

## Windows 下搭建
安装Git for Windows、Android Studio、JDK

### 获取Flutter SDK
打开git bash，输入命令`git clone -b beta https://github.com/flutter/flutter.git`，添加flutter/bin到环境变量中

PS:如果很慢，把github.com的ip写到hosts里面去，测延迟去站长之家

配置系统变量，新建变量名PUB_HOSTED_URL，变量值`https://pub.flutter-io.cn`，新建变量名FLUTTER_STORAGE_BASE_URL，变量值`https://storage.flutter-io.cn`

重启Windows

- 运行flutter doctor，会下载必要的包
- Android Studio 安装flutter插件

## Linux 下搭建
安装Android Studio、JDK

### 获取Flutter SDK
打开git bash，输入命令
```
git clone -b beta https://github.com/flutter/flutter.git
export PUB_HOSTED_URL=https://pub.flutter-io.cn //国内用户需要设置
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn //国内用户需要设置
export PATH=`pwd`/flutter/bin:$PATH
```
PS:如果很慢，把github.com的ip写到hosts里面去，测延迟去站长之家

- 运行flutter doctor，会下载必要的包
- Android Studio 安装flutter插件

## Mac 下搭建
没Mac，不记录

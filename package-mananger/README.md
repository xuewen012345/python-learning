# Python安装

yum -y install epel-release

yum install python36u
yum install python27
ln -s /usr/bin/python3.6 /usr/bin/python3
ln -s /usr/bin/python2.7 /usr/bin/python2

# 包管理
easy_install和pip都可以
easy_install的用法


1） 安装一个包
$ easy_install <package_name>
$ easy_install "<package_name>==<version>"

2) 升级一个包
$ easy_install -U "<package_name>>=<version>"

pip的用法

1) 安装一个包
 $ pip install <package_name>
$ pip install <package_name>==<version>

2) 升级一个包 (如果不提供version号，升级到最新版本）
$ pip install --upgrade <package_name>>=<version>

3）删除一个包
$ pip uninstall <package_name>

# 工具

Pycharm

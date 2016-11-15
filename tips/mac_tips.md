
1. Mac OS 之brew无权限解决方法

最近使用brew安装软件，发现不论安装什么都会报出Error: Cowardly refusing to sudo brew install 提示无root权限，登陆到root权限后也会报错。检查brew发现该工具无root权限，执行一下sudo chown root:wheel /usr/local/bin/brew 即可

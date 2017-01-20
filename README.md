# toolbox
> 日常工作与生活的工具与资料收集

## Contents  

- [配置文件](#配置文件)  
- [APP](#app)
- [服务器基本设置](#服务器基本设置)


## 配置文件  

- [Pycharm](./confs/pycharm/settings.jar)  Version:2016.2.3  
- [Visual Studio Code](./confs/vscode/settings.json)
- [VIM](https://github.com/mutoulbj/my-vim)


## APP


## 服务器基本设置

#### Ubuntu 安装源修改  

`sed -i sed -i s/archive.ubuntu.com/mirrors.aliyun.com/g /etc/apt/sources.list`  

#### pip 源修改  

新增 `.pip/pip.conf` 文件，并写入以下内容

```
[global]
index-url = http://mirrors.aliyun.com/pypi/simple
trusted-host = mirrors.aliyun.com
```  


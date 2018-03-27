# lnmp-zabbix_server

## 环境：
#### 1、centos7

## 部署步骤：
#### 1、部署lnmp环境
```
yum -y install git
cd /usr/src
git clone https://github.com/chendao2015/lnmp-zabbix_server.git
cd lnmp-zabbix_server
tar xf lnmp.tar.xz
chmod +x lnmp.sh
./lnmp.sh
```

#### 2、部署zabbix-server
```
chmod +x zabbix_server.sh
./zabbix_server.sh
```

## 说明
#### mysql默认配置的root用户密码是Changqin2018.
#### mysql端口是默认的3306
#### zabbix数据库默认为zabbix
#### zabbix数据库用户默认为zabbix
#### zabbix数据库密码默认为ChangqinZabbix2018.

#### zabbix的web管理界面帐号为Admin，密码为zabbix

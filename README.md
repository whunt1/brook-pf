# Brook 端口转发 一键管理脚本

原 逗比 Brook 端口转发 一键管理脚本 修改版
增加对动态域名的支持，开启监控后自动更新域名IP

## whunt1 20220321 修复版本

适配当前最新版本 brook v20220404

## ECIAP 再修改分支

尝试修复 <https://github.com/yulewang/brook/issues/4> 此问题的分支

## 快速部署

- For RHEL / CentOS:

```bash
sudo yum install bind-utils -y && yum install wget -y && wget https://raw.githubusercontent.com/whunt1/brook-pf/master/brook-pf-mod.sh && chmod +x brook-pf-mod.sh && bash brook-pf-mod.sh
```

- For Debian / Ubuntu:

```bash
sudo apt-get install dnsutils -y && sudo apt-get install wget -y && wget https://raw.githubusercontent.com/whunt1/brook-pf/master/brook-pf-mod.sh && chmod +x brook-pf-mod.sh && bash brook-pf-mod.sh
```

## 其他事项

- 对于 **v20210616 及以前版本** 请使用如下命令

- For RHEL / CentOS:

```bash
sudo yum install bind-utils -y && yum install wget -y && wget https://raw.githubusercontent.com/ECIAP/brook/master/brook-pf-mod.sh && chmod +x brook-pf-mod.sh && bash brook-pf-mod.sh
```

- For Debian / Ubuntu:

```bash
sudo apt-get install dnsutils -y && sudo apt-get install wget -y && wget https://raw.githubusercontent.com/ECIAP/brook/master/brook-pf-mod.sh && chmod +x brook-pf-mod.sh && bash brook-pf-mod.sh
```

- 对于 **v20200801 以及更早的brook版本** 请使用如下命令

```bash

For RHEL / CentOS:
yum install wget -y && wget https://raw.githubusercontent.com/ECIAP/brook/master/brook-pf-mod-old.sh && chmod +x brook-pf-mod-old.sh && bash brook-pf-mod-old.sh

For Debian / Ubuntu:
yum install wget -y && wget https://raw.githubusercontent.com/ECIAP/brook/master/brook-pf-mod-old.sh && chmod +x brook-pf-mod-old.sh && bash brook-pf-mod-old.sh

```

- 快速前往 Brook release
  
  <https://github.com/txthinking/brook/releases>

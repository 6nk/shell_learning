## 查找某个命令（如ping）是哪个包安装的

- $ which ping
- /bin/ping
- $what-provides /bin/ping
- iputils-ping: /bin/ping

## aptitide 

- 软件更新

  - 保守

    aptitude safe-upgrade

  - 不检查包依赖关系

    aptitude dist-upgrade

    aptitude full-dist-upgrade

- 软件卸载（以wine为例）

  - 保留数据和配置

    aptitude remove wine

  - 全部删除

    aptitude purge wine

## yum

- 安装软件

  - 在线安装

    yum install package_name

  - 本地安装

    yum localinstall package_name

 - 软件更新

     - 列出所有可用更新
       yum list updates

     - 更新指定软件

       yum update package_name

     - 更新全部软件

       yum update

- 软件卸载

  - 保留数据和配置

    yum remove package_name

  - 全部删除

    yum erase package_name
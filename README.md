# TOUGHRADIUS

[![](https://badge.imagelayers.io/talkincode/toughradius:v2.svg)](https://imagelayers.io/?images=talkincode/toughradius:v2 'Get your own badge on imagelayers.io')

## TOUGHRADIUS 简介

TOUGHRADIUS是一个开源的Radius服务软件，采用于AGPL许可协议发布。

TOUGHRADIUS支持标准RADIUS协议，提供完整的AAA实现。支持灵活的策略管理，支持各种主流接入设备并轻松扩展，具备丰富的计费策略支持。

TOUGHRADIUS支持使用Oracle, MySQL, PostgreSQL, MSSQL等主流数据库存储用户数据，并支持数据缓存，极大的提高了性能。

TOUGHRADIUS支持Windows，Linux，BSD跨平台部署，部署使用简单。

TOUGHRADIUS提供了RADIUS核心服务引擎与Web管理控制台,用户自助服务三个子系统，核心服务引擎提供高性能的认证计费服务，Web管理控制台提供了界面友好，功能完善的管理功能。用户自助服务系统提供了一个面向终端用户的网上服务渠道。

TOUGHRADIUS网站：http://www.toughradius.net

## Linux 快读部署

    $ wget https://github.com/talkincode/ToughRADIUS/raw/master/installer -O /opt/installer
    $ chmod +x  /opt/installer

### 一键安装docker环境

    $ /opt/installer docker

### 一键部署mysql与toughradius实例

    $ /opt/installer with_mysql

### 一键部署与已有MySQL数据库对接

    $ /opt/installer standalone


访问 http://server:1816  进入管理系统，默认用户名密码是 admin/root

## TOUGHRADIUS 文档

http://docs.toughradius.net

## TOUGHRADIUS 商业授权

[TOUGHRADIUS 商业授权](#) (https://github.com/talkincode/ToughRADIUS/blob/master/Commerical-license.rst)
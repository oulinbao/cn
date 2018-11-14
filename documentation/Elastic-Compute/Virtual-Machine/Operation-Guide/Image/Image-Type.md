# 镜像类型
## 京东云镜像分为四种类型
### 官方镜像
官方镜像是由京东云提供和维护的公共镜像，基于上游官方发行厂商提供Linux和Windows的多个发行版本（Windows镜像目前免费提供正版License）提供基础操作系统、初始化组件及部分预装软件，所有用户均可以使用。
### 私有镜像
私有镜像是基于用户自有实例创建自定义镜像，您可以为已部署业务的主机制作镜像，基于此镜像快速创建多个具有相同配置和软件环境的主机。您可以将私有镜像共享给同其他京东云用户，被共享镜像会显示在目标用户同区域的共享镜像列表中。私有镜像支持删除和基本信息修改。
### 共享镜像
共享镜像是由其他京东云用户通过镜像共享功能所分享而来的用户自定义镜像，展示区域与被共享的私有镜像相同。共享镜像仅可用于创建实例，不可进行基本信息修改、删除等操作，若发起共享的用户取消了共享，则该镜像会从列表中自动删除。
### 镜像市场镜像
镜像市场镜像是由入驻云市场的服务商所提供的镜像，集成了针对不同业务场景的运行环境或软件，方便用户快速部署业务。
## 官方镜像发行版本
|   **操作系统**  |  **系统版本**   |
| --- | --- |
|   Windows Server  |  2016 数据中心版 中文版<br>2012 R2 标准版 中文版<br>2008 R2 数据中心版 中文版|
|  CentOS   |  7.4、7.3、7.2、7.1、7.2  NAT Gateway<br>6.9、6.8、6.6、6.5   |
|   Ubuntu  |  16.04、14.04   |

**注：京东云目前提供的官方镜像均为64位镜像**
## 镜像使用限制
官方镜像：所有用户均可以使用。

私有镜像：仅创建者和共享对象可以使用，用户每个地域下可以创建不多于5个私有镜像；用户可以将一个镜像分享给不多于5个京东云用户。

共享镜像：仅创建者和共享对象可以使用，用户每个地域下可以接受不多于5个共享镜像。

镜像市场镜像：所有用户均可以使用。可通过控制台或云市场选择镜像创建主机，也可通过重置系统更换镜像为镜像市场镜像。
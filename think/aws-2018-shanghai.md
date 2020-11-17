# 亚马逊2018上海(2018-06-29)

![](https://me.wangyaqi.cn/s/aws2018/view.jpg)

* 整体技术性不强，配不上亚马逊这个牌子

# 内容
1. 亚马逊服务
1. 第三方的亚马逊服务，特别是云服务供应商相关的

# 亚马逊新技术
## 无服务器架构
* lambda：支持4种语言，本质是web服务(apache/tomcat)

## 数据湖
* 支持各种数据和文件，有配套分析服务

# AI
* [皮肤分析](https://www.yimei.ai/)
  1. 自开发标注系统，标注后自动训练
* [手术辅助](http://www.mvisioner.com/)

# 12-Factors原则与云端应用
* 应用包：依赖项，代码，库文件
* 发布：应用包 + 配置。所有环境等价(应用包一个)，通过运行时的配置参数来设置运行环境
* docker的log通过stdout获取
* 配置需外部独立管理

# 资料
* [12-Factors原则与云端应用.pdf](https://me.wangyaqi.cn/s/aws2018/12-Factors原则与云端应用.pdf)
* [文件下载](https://app-aws-m.scrmtech.com/svip/sapIndex/SapSourceList?pf_uid=5191_19&page=0&source=1&pf_type=3)

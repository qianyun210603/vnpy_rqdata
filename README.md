# vn.py框架的RQData数据服务接口

<p align="center">
  <img src ="https://vnpy.oss-cn-shanghai.aliyuncs.com/vnpy-logo.png"/>
</p>

<p align="center">
    <img src ="https://img.shields.io/badge/version-2.9.38.1-blueviolet.svg"/>
    <img src ="https://img.shields.io/badge/platform-windows|linux-yellow.svg"/>
    <img src ="https://img.shields.io/badge/python-3.7-blue.svg" />
    <img src ="https://img.shields.io/github/license/vnpy/vnpy.svg?color=orange"/>
</p>

## 说明

基于米筐rqdatac模块的2.9.38版本开发，支持以下中国金融市场的K线和Tick数据：

* 期货和期货期权：
  * CFFEX：中国金融期货交易所
  * SHFE：上海期货交易所
  * DCE：大连商品交易所
  * CZCE：郑州商品交易所
  * INE：上海国际能源交易中心
* 贵金属现货：
  * SGE：上海黄金交易所
* 股票和ETF期权：
  * SSE：上海证券交易所
  * SZSE：深圳证券交易所

注意：需要购买相应的数据服务权限，可以通过[该页面](https://www.ricequant.com/welcome/purchase?utm_source=vnpy)申请试用。


## 安装

安装需要基于2.6.0版本以上的[VN Studio](https://www.vnpy.com)。

直接使用pip命令：

```
pip install vnpy_rqdata
```


或者下载解压后在cmd中运行：

```
python setup.py install
```

## 使用

在vn.py中使用米筐RQData时，需要在全局配置中填写以下字段信息：

|名称|含义|必填|举例|
|---------|----|---|---|
|datafeed.name|名称|是|rqdata|
|datafeed.username|用户名|是|license|
|datafeed.password|密码|是|bqIA9yH6GY3ie4jtDwlLauQJ90XX7qJ9F4My-DxzS|

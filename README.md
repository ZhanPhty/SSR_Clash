# Clash规则碎片

主要文件在clash文件夹下，只是一些规则碎片，可以配合一些订阅转换进行使用。

项目里/Clash/config/目录下存放的是 [subconverter](https://github.com/tindy2013/subconverter/blob/master/README-cn.md#外部配置)的 配置示例

| 文件                   | 类型                 | 解释                                                         |
| ---------------------- | -------------------- | ------------------------------------------------------------ |
| ProxyLite.list         | 规则碎片-代理补充列表  | 需要代理的列表           |
| Direct.list            | 规则碎片-直连补充列表  | 国内域名不解析时，防止走代理使用           |
| BT.list                | 规则碎片-BT下载  | BT下载走直连           |
| PT.list                | 规则碎片-PT下载  | PT下载走直连           |
| GeneralClashConfig.yml | clash配置文件        | 放行一堆国内的常用域名，配合系统代理更牛逼。 配置很全，自带中文注释。可以自行使用 |
| pref.ini               | subconverter配置文件 | 更改了一些基础配置                      |

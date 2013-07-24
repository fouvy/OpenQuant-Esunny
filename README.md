# OpenQuant内盘期货历史数据插件

## 目的
将OpenQuant与国内的Esunny进行对接，让OpenQuant直接能下载期货历史数据

## 设计思路
请参考OpenQuant-CTP

## 安装
QD根目录\ini\framework.xml添加
`<plugin enabled="True" assembly="QuantBox.OQ.Esunny" type="QuantBox.OQ.Esunny.EsunnyProvider" />`

动态库拷贝到QD根目录\bin文件夹下面

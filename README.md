## 欢迎来到 Cloud Studio ##

本项目来源于[腾讯云](https://www.cloudstudio.net/?utm=csdnblog&login=from_csdn) Cloud Studio 实战训练营》>《[腾讯云](https://marketing.csdn.net/p/06a21ca7f4a1843512fa8f8c40a16635?login=from_csdn) Cloud Studio 实战训练营》的参赛作品，该作品在[腾讯云](https://marketing.csdn.net/p/06a21ca7f4a1843512fa8f8c40a16635?login=from_csdn) Cloud Studio 中运行无误。

##  项目介绍 ##

本项目基于腾讯云 Cloud Studio 的Python环境构建，可以实现实时数据可视化效果。

以天气数据为例，可以灵活替换为其它数据源。

使用Echarts作为图表展示组件，也可以方便的切换为其它图表类型。

数据每分钟自动刷新，显示变化趋势，实用性强，如有需要也可以永久保存历史数据。

## 项目启动 ##

项目无需额外添加其它类库，等待自动初始化即可。

完整的启动命令为：

```bash
pip install -i https://mirrors.tencent.com/pypi/simple/ -r ./requirements.txt && bash /usr/bin/start-vnc-session.sh && python ./app.py
```

后续如果需要重新启动，只需要在web目录下执行:
```bash
python ./app.py
```

需要注意的是，本项目中使用的API KEY基于免费额度，为了帮助大家体验完整效果并为隐去，请不要持续长期使用，可以简单的到官网生成自己的API KEY，或者使用其它的数据接口，谢谢。
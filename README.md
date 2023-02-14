# TatatouBot2

基于NoneBot2的骰子机器人塔塔骰

## 当前功能

## 依赖

1. python >= 3.7.3
2. 如果有NoneBot v1则卸载 `pip uninstall nonebot`
3. 本代码测试使用的NoneBot版本是 nonebot2==2.0.0b4

## 使用

1. 安装脚手架nb-cli

   ```shell
   pip install nb-cli
   
   # 国内速度慢可以用阿里源加速，或者别的源，命令如下
   pip install nb-cli -i https://mirrors.aliyun.com/pypi/simple/
   ```

2. 安装适配器

   ```
   nb adapter install nonebot-adapter-onebot
   ```

3. 下载本项目代码，并进入文件夹

   ```
   git clone https://github.com/aaron-lii/TataruBot2.git
   cd TataruBot2
   ```

4. 根据需要修改配置文件`.env.dev`，更多信息见NoneBot2官方文档

5. 启动机器人

   ```
   nb run
   ```

6. 使用go-cqhttp连接机器人，该部分参考go-cqhttp官方文档。需要注意的是配置中反向websocket设置参考文档https://adapter-onebot.netlify.app/docs/guide/setup

## 备注

NoneBot2官方文档：https://v2.nonebot.dev/

NoneBot2 github：https://github.com/nonebot/nonebot2

go-cqhttp连接配置：https://adapter-onebot.netlify.app/docs/guide/setup

go-cqhttp github：https://github.com/Mrs4s/go-cqhttp

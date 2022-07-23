# Portune多合一魔改版

Portune是一个适用于[HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot) v2的PCR角色每日运势插件，在nonebot插件vortune原代码基础上改动以适配Hoshino

魔改版融合了原神，pcr，东方，赛马娘四个主题（本来想搞vtb，但好像有几个暴雷了）

~~抄袭~~仿一个群友(明见？)的[bot](https://help.pcrlink.cn/instructions/fortune/)(可以去买来玩玩，很多功能蛮有意思的)艹，真喜欢他的碧蓝航线底图，可惜没找到，可能自己搞得？

### ★ 如果你喜欢的话，请给仓库点一个star支持一下23333 ★

## 本项目地址：

[https://github.com/SonderXiaoming/portune](https://github.com/SonderXiaoming/portune)

## 安装方法：

- 将`portune`文件夹复制到`hoshino\modules`文件夹下（原来有就删了他）；
- 打开`portune`文件夹下的`portune.py`，按照注释选择编辑：
    1.帮助文本
    2.每日抽签次数
- 将`portunedata`文件夹复制到hoshino的资源文件夹`res\img`文件夹下（原来有了就删除再复制进去）；
- 最后记得在`hoshino\config\__bot__.py`的`MODULES_ON`中加上`portune`

## 已知问题（懒得搞，最好pr）

1. 模块化安装主题（最好就是每个主题写个自己的描述文件，放在一个文件夹中，像加载插件一样，自动导入，我这里写死了，要加就要改代码）

2. 固定主题指令

3. 分群安装主题

4. 赛马娘底图和运势文本补充（hoshino群文件里文本怎么只整到21，后面是弃坑了？）

5. 更多主题

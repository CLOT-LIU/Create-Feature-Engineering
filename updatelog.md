# 机械动力：特性工程更新日志
这是为`机械动力：特性工程`整合包玩家与开发者撰写的更新日志
开发者进行撰写时请在相应分类下简单描述本次更改的内容并署名是谁进行的更改

## alpha-0.0.5版本

### 游戏内容添加
#### Mod
1. 添加了`Compressed Create Recipes`——hao888myt
#### 物品
1. 添加了`矿石饲料`——hao888myt
#### 方块
1. 添加了`乌龟化石`——hao888myt
2. 为`机械动力：原子核动`的`深层铀矿石`和`深层铅矿石`添加了`#c:ores_in_ground/deepslate`——hao888myt
3. 为`机械动力`的`深层锌矿石`添加了`#c:ores_in_ground/deepslate`——hao888myt
#### 特性
1. 将`矿石饲料`喂给`乌龟`后，`乌龟`分别有20%，10%，10%，50%，10%的概率长出`煤矿石`、`铁矿石`、`红石矿石`、`青金石矿石`和`铜矿石`——hao888myt
2. 用`矿物饲料`右击`乌龟化石`后，可以在以`乌龟化石`为中心3x3x3的区域内将`矿物饲料`喂给`乌龟`——hao888myt
#### 配方
1. 添加了`煤炭`在`压缩机`中加压反应并加热生产`焦炭`的配方——hao888myt
2. 添加了`矿石饲料`的配方——hao888myt
#### 思索
1. `光谱世界`的`方块探测器`——hao888myt
#### 代码
1. 添加了`AddItemLang(key, value)`——hao888myt

### 游戏内容修改
#### Mod
1. 将`铁砧工艺`的版本换成了`1.4.1-rc-2`——hao888myt
#### 配方
1. 修改了`树脂`的配方——hao888myt

### 游戏内容移除
#### Mod
1. 删除了`True Ending:Ender Dragon Overaul`——hao888myt
2. 删除了`Packetfixer`——hao888myt
3. 删除了`Pick Block Pro（选择方块专业版）`——hao888myt
#### 配方
1. 删除了`流体构件`的配方——hao888myt

### bug修复
####
1. 修复了`首次进入末地`时，`游戏会崩溃`的bug——hao888myt
2. 修复了`部分树叶`无法在`振动台`上获得对应树苗的bug——hao888myt
3. 修复了`催化剂`催化`含水方块`后，原地会留下一格水的bug——hao888myt
4. 修复了`机械手`使用`催化剂`催化`魔盒`导致坏档的bug（通过禁用机械手催化魔盒实现）——hao888myt
5. 修复了`基岩刷石机`无法生效的bug——hao888myt
6. 修复了`CobbleGenRandomizer`默认配置文件扰乱刷石机结果的bug——hao888myt
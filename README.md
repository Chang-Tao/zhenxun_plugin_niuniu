# zhenxun_plugin_niuniu
真寻群内小游戏插件-牛牛大作战

## 原项目 [molanp/zhenxun_plugin_niuniu](https://github.com/molanp/zhenxun_plugin_niuniu)
在将其部署到真寻bot中时, 遇到以下问题
1. 无法使用排行榜
2. 排行榜使用image方式展示
3. image的函数(buildmap)有问题, 但不知道是什么问题
4. 排行榜排名显示异常
##
解决方法:
由于本人python能力有限, 在GPT的帮助下对buildmap函数进行了修改, 启用了iamge方式展示排行榜,而是用文本进行展示

## 使用方法
下载压缩包，解压并放入`plugin`文件夹或其他自定义文件夹中
参考路径 zhenxun/plugins/zhenxun_plugin_niuniu

## 指令
|指令|功能描述|
|---|---|
|注册牛牛|注册你的牛牛|
|注销牛牛|删除你的牛牛|
|jj [@user](或"击剑)|与注册牛牛的人进行击剑，对战结果影响牛牛长度|
|我的牛牛|查看自己牛牛长度|
|牛牛长度排行|查看本群正数牛牛长度排行|
|牛牛深度排行|查看本群负数牛牛深度排行|
|打胶|对自己的牛牛进行操作，结果随机|

## 依赖

正常情况真寻的虚拟环境里附带此模块
```powershell
pip install ujson
```

## 说明
群友长度数据位于插件文件夹中的`data/long.json`中

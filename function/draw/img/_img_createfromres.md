---
description: 图像_创建自资源包
---


## 声明

|动态库命令| 返回值类型|库文件名|参数量| 备注|
|:--:|:--:|:--:|:--:|:--:|
| _img_createfromres |  整数型 |  libexdui.dll | 3 | 图像_创建自资源包，成功返回0 |

## 参数列表

|  参数名  |  类型  | 传址 | 数组 | 可空(NULL) |     备注     |
| :------: | :----: | :--: | :--: | :--------: | :----------: |
|   hRes   | 整数型 |  -   |  -   |     -      |  资源包指针  |
| atomPath | 整数型 |  -   |  -   |     -      |  原子号路径  |
|   hImg   | 整数型 |  √   |  -   |     -      | 返回图像指针 |


# 示例

## 易语言


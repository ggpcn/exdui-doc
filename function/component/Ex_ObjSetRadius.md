---
description: 控件_置圆角度
---




## 声明

|   动态库命令    | 返回值类型 |   库文件名   | 参数量 |      备注      |
| :-------------: | :--------: | :----------: | :----: | :------------: |
| Ex_ObjSetRadius |   逻辑型   | libexdui.dll |   6    | 设置控件圆角度 |

## 参数列表

|   参数名    |  类型  | 传址 | 数组 | 可空(NULL) |   备注   |
| :---------: | :----: | :--: | :--: | :--------: | :------: |
|    hObj     | 整数型 |  -   |  -   |     -      | 控件句柄 |
|   topleft   | 小数型 |  -   |  -   |     -      |  左上角  |
|  topright   | 小数型 |  -   |  -   |     -      |  右上角  |
| bottomright | 小数型 |  -   |  -   |     -      |  右下角  |
| bottomleft  | 小数型 |  -   |  -   |     -      |  左下角  |
|   fUpdate   | 逻辑型 |  -   |  -   |     -      | 立即更新 |


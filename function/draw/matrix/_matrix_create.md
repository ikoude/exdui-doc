---
description: 矩阵_创建
---




## 声明

|动态库命令| 返回值类型|库文件名|参数量| 备注|
|:--:|:--:|:--:|:--:|:--:|
| _matrix_create |  整数型 |  libexdui.dll | 0 | 矩阵_创建，成功返回zh |


# 示例

## 易语言

```basic
如果 (_matrix_create (hFont，dstImg) ＝ 0)
    输出调试文本 (“创建成功”)
 否则
    输出调试文本 (“创建失败”)
```



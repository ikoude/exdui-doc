---
description: 画刷_创建自图像
---

### Syntax / 函数原型

```C++
HBRUSH __stdcall 
_brush_createfromimg (
    HIMG hImg
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _brush_createfromimg, 整数型, "libexdui.dll", "_brush_createfromimg", 公开, 
    .参数 hImg, 整数型,  , 
```

---

### Parameters / 参数

`hImg`

Type: **HIMG**

图像句柄

---

### Return Value / 返回值

Type: HBRUSH

创建成功 返回画刷句柄

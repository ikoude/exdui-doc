---
description: 布局_投送消息
---

### Syntax / 函数原型

```C++
int __stdcall 
_layout_notify (
    int hLayout,
    int nEvent,
    int wParam,
    int lParam
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_notify, 整数型, "libexdui.dll", "_layout_notify", 公开, 
    .参数 hLayout, 整数型,  , 
    .参数 nEvent, 整数型,  , 
    .参数 wParam, 整数型,  , 
    .参数 lParam, 整数型,  , 
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`nEvent`

Type: **INT32**

事件ID

`wParam`

Type: **INT32**

附加参数, 具体参考事件ID

`lParam`

Type: **INT32**

附加参数, 具体参考事件ID

---

### Return Value / 返回值

Type: INT32

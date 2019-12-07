---
description: 布局_删除组件
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_deletechild (
    int hLayout,
    int hObj
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_deletechild, 逻辑型, "libexdui.dll", "_layout_deletechild", 公开,
    .参数 hLayout, 整数型,  ,
    .参数 hObj, 整数型,  ,
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`hObj`

Type: **HANDLE**

组件句柄

---

### Return Value / 返回值

Type: BOOL

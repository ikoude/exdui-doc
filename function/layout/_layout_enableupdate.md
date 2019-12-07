---
description: 布局_启用更新
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_enableupdate (
    int hLayout,
    bool fUpdateable
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_enableupdate, 逻辑型, "libexdui.dll", "_layout_enableupdate", 公开, 
    .参数 hLayout, 整数型,  , 
    .参数 fUpdateable, 逻辑型,  , 
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`fUpdateable`

Type: **BOOL**

是否更新

---

### Return Value / 返回值

Type: BOOL

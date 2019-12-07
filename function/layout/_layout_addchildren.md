---
description: 布局_添加组件集
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_addchildren (
    int hLayout,
    bool fDesc,
    int dwObjClassATOM,
    int nCount
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_addchildren, 逻辑型, "libexdui.dll", "_layout_addchildren", 公开,
    .参数 hLayout, 整数型,  ,
    .参数 fDesc, 逻辑型,  ,
    .参数 dwObjClassATOM, 整数型,  ,
    .参数 nCount, 整数型, 传址 ,
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`fDesc`

Type: **BOOL**

是否为倒序

`dwObjClassATOM`

Type: **INT32**

0或空为所有

`nCount`

Type: **INT32**

加入的数量

---

### Return Value / 返回值

Type: BOOL

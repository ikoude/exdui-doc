---
description: 布局_注册
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_register (
    int nType,
    int lpfnLayoutProc
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_register, 逻辑型, "libexdui.dll", "_layout_register", 公开, 
    .参数 nType, 整数型,  ,
    .参数 lpfnLayoutProc, 整数型,  ,
```

---

### Parameters / 参数

`nType`

Type: **INT32**

布局类型

`lpfnLayoutProc`

Type: **CALLBACK**

布局管理器回调指针

---

### Return Value / 返回值

Type: BOOL

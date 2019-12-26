---
description: Ex_释放资源
---

### Syntax / 函数原型

```C++
void __stdcall 
Ex_ResFree (
    HRESOURCE hRes,
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ResFree, , "libexdui.dll", "Ex_ResFree", 公开, 
    .参数 hRes, 整数型,  , 
```

---

### Parameters / 参数

`hRes`

Type: **HRESOURCE**

资源包句柄

---

释放一个资源

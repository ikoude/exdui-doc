---
description: 置最后错误
---

### Syntax / 函数原型

```C++
void __stdcall 
Ex_SetLastError (
    int nError
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_SetLastError, , "libexdui.dll", "Ex_SetLastError", 公开,
    .参数 nError, 整数型,  , 
```

---

### Parameters / 参数

`nError`

Type: **INT32**

错误代码 参见 [ERROR_EX_]("#")

---

### Return Value / 返回值

Type: INT32

设置最后错误代码

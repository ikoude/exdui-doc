---
description: 字符串取原子号
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_Atom (
    LPCTSTR lptstring
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_Atom, 整数型, "libexdui.dll", "Ex_Atom", 公开,
    .参数 lptstring, 整数型,  , 
```

---

### Parameters / 参数

`lptstring`

Type: **LPCTSTR**

传入的字符串

---

### Return Value / 返回值

Type: INT32

获取字符串唯一原子号

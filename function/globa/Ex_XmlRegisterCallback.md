---
description: 注册XML键值回调
---

### Syntax / 函数原型

```C++
void __stdcall 
Ex_XmlRegisterCallback (
    int atomValue,
    int pfnCallback
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_XmlRegisterCallback, , "libexdui.dll", "Ex_XmlRegisterCallback", 公开, 
    .参数 atomValue, 整数型,  , 
    .参数 pfnCallback, 子程序指针,  , 
```

---

### Parameters / 参数

`atomValue`

Type: **INT32**

原子值

`pfnCallback`

Type: **INT32**

回调函数

---

### Return Value / 返回值

Type: INT32

注册XML键值回调

---
description: Ex加载内存主题包
---

### Syntax / 函数原型

```C++
HANDLE __stdcall 
Ex_ThemeLoadFromMemory (
    LPVOID lpData,
    DWORD  dwDataLen,
    LPVOID lpKey,
    DWORD  dwKeyLen,
    bool   bDefault
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ThemeLoadFromMemory, 整数型, "libexdui.dll", "Ex_ThemeLoadFromMemory", 公开, 加载主题包
    .参数 lpData, 整数型,  , 
    .参数 dwDataLen, 整数型,  , 
    .参数 lpKey, 整数型,  , 
    .参数 dwKeyLen, 整数型,  , 
    .参数 bDefault, 逻辑型,  , 
```

---

### Parameters / 参数

`lpData`

Type: **LPVOID**

主题包缓冲区指针

`dwDataLen`

Type: **DWORD**

主题包缓冲区长度

`lpKey`

Type: **LPVOID**

密钥指针

`dwKeyLen`

Type: **DWORD**

密钥长度

`bDefault`

Type: **BOOL**

\-

---

### Return Value / 返回值

Type: HANDLE

从内存加载主题包 返回主题包句柄
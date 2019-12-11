---
description: Ex加载主题包
---

### Syntax / 函数原型

```C++
HANDLE __stdcall 
Ex_ThemeLoadFromFile (
    LPCWSTR lptszFile,
    LPVOID  lpKey,
    DWORD   dwKeyLen,
    bool    bDefault
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ThemeLoadFromFile, 整数型, "libexdui.dll", "Ex_ThemeLoadFromFile", 公开, 
    .参数 lptszFile, 整数型,  , 
    .参数 lpKey, 整数型,  , 
    .参数 dwKeyLen, 整数型,  , 
    .参数 bDefault, 逻辑型,  , 
```

---

### Parameters / 参数

`lptszFile`

Type: **LPCWSTR**

文件路径

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

加载主题包 返回主题包句柄
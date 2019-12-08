---
description: 初始化
---

### Syntax / 函数原型

```C++
bool __stdcall 
Ex_Init (
    HINSTANCE hInstance,
    DWORD     dwGlobalFlags,
    HCURSOR   hDefaultCursor,
    LPCSTR    lpszDefaultClassName,
    LPVOID    lpDefaultTheme,
    DWORD     dwDefaultThemeLen,
    LPVOID    lpDefaultI18N,
    DWORD     dwDefaultI18NLen
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_Init, 逻辑型, "libexdui.dll", "Ex_Init", 公开,
    .参数 hInstance, 整数型,  ,
    .参数 dwGlobalFlags, 整数型,  ,
    .参数 hDefaultCursor, 整数型,  ,
    .参数 lpszDefaultClassName, 整数型,  ,
    .参数 lpDefaultTheme, 整数型,  ,
    .参数 dwDefaultThemeLen, 整数型,  ,
    .参数 lpDefaultI18N, 整数型,  ,
    .参数 dwDefaultI18NLen, 整数型,  ,
```

---

### Parameters / 参数

`hInstance`

Type: **HINSTANCE**

动态库(DLL)的实例句柄 可为NULL

`dwGlobalFlags`

Type: **DWORD**

全局初始化标识 参见 [EXGF](../../const/EXGF.md)

`hDefaultCursor`

Type: **HCURSOR**

默认鼠标指针句柄 可为NULL

`lpszDefaultClassName`

Type: **LPCSTR**

默认窗口类名 可为NULL

`lpDefaultTheme`

Type: **LPCSTR**

默认主题包指针

`dwDefaultThemeLen`

Type: **DWORD**

默认主题包缓冲区长度

`lpDefaultI18N`

Type: **LPCSTR**

默认语言包指针 

`dwDefaultI18NLen`

Type: **DWORD**

默认语言包指针缓冲区长度

---

### Return Value / 返回值

Type: BOOL

初始化引擎
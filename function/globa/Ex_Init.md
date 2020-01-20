---
description: 初始化
---

### Description / 描述

使用 ExDUI 前，请务必调用 Ex_Init。

创建并显示一个自绘窗口的整体流程为：

**初始化引擎** -> [创建窗口](../window/Ex_WndCreate.md) -> [绑定窗口](./Ex_DUIBindWindow.md) -> 设置窗口属性 -> 显示窗口 -> [消息循环](../window/Ex_WndMsgLoop.md) -> 销毁窗口


### Syntax / 函数原型

```C++
bool __stdcall 
Ex_Init (
    HINSTANCE hInstance,
    DWORD     dwGlobalFlags,
    HCURSOR   hDefaultCursor,
    LPCTSTR   lpszDefaultClassName,
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

Type: **LPCTSTR**

默认窗口类名 可为NULL

`lpDefaultTheme`

Type: **LPVOID**

默认主题包指针

`dwDefaultThemeLen`

Type: **DWORD**

默认主题包缓冲区长度

`lpDefaultI18N`

Type: **LPVOID**

默认语言包指针 

`dwDefaultI18NLen`

Type: **DWORD**

默认语言包指针缓冲区长度

---

### Return Value / 返回值

Type: BOOL

初始化引擎

### Example / 使用样例

**易语言**

```Elang
.版本 2
.局部变量 bin, 字节集
bin ＝ 读入文件 (“./Default.ext”)
Ex_Init (GetModuleHandle (0), 位或 (#EXGF_DPI_ENABLE, #EXGF_RENDER_METHOD_D2D, #EXGF_MENU_ALL), 0, 0, 取指针_字节集型 (bin), 取字节集长度 (bin), 0, 0)
' 创建窗口
bin ＝ A2W (“模态对话框”)
m_hWnd ＝ Ex_WndCreate (0, 0, 取指针_字节集型 (bin), 0, 0, 400, 300, 0, 0)
```

（编者内心：易语言的这个 bin 没有像 C++ 一样进行 Free 的操作，不知道会不会内存泄漏）


**C++**
```C++
//读入主题文件
ExData dataTheme;
ExReadAllBytes(L"../ExDirectUI4.1/Default.ext", &dataTheme);
//初始化, 下面的就和易语言一样了
Ex_Init(GetModuleHandle(NULL), 0, NULL, NULL, dataTheme.ptr, dataTheme.len, NULL, 0);
		
//注意使用完毕后释放数据
ExDataFree(&dataTheme);
// 创建窗口
HWND hWnd = Ex_WndCreate(NULL, NULL, L"测试", 50, 50, 400, 400, 0, 0);
```

(到这一步窗口时显示不出来的，因为还要绑定、显示、消息循环、销毁)

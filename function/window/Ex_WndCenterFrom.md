---
description: Ex窗口居中
---

### Syntax / 函数原型

```C++
void __stdcall 
Ex_WndCenterFrom (
    int hWnd,
    int hWndFrom,
    bool bFullScreen
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_WndCenterFrom, , "libexdui.dll", "Ex_WndCenterFrom", 公开, 
    .参数 hWnd, 整数型,  , 
    .参数 hWndFrom, 整数型,  , 
    .参数 bFullScreen, 逻辑型,  , 
```

---

### Parameters / 参数

`hWnd`

Type: **HWND**

欲居中的原始窗口

`hWndFrom`

Type: **HWND**

欲居中的目标窗口 如果为 NULL 则为屏幕居中

`bFullScreen`

Type: **BOOL**

是否全屏模式

---

### Return Value / 返回值

窗口居中
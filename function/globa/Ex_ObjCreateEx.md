---
description: 创建组件
---

### Description / 描述

您可以使用该方法创建各种各样的组件。

通过指定不同的 `lptszClassName`，您可以使用的组件数量多达 16+ 

有关 `lptszClassName` 的详细内容[请点我](../../reference/default_obj_classes.md)

### Syntax / 函数原型

```C++
HWND __stdcall 
Ex_ObjCreateEx (
    DWORD dwStyleEx, 
    LPCWSTR lptszClassName, 
    LPCWSTR lptszObjTitle, 
    DWORD dwStyle, 
    int x, 
    int y, 
    int width, 
    int height, 
    HWND hParent, 
    int nID, 
    DWORD dwTextFormat, 
    LPARAM lParam, 
    HWND hTheme, 
    int lpfnMsgProc
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ObjCreateEx, 整数型, "libexdui.dll", "Ex_ObjCreateEx", 公开, 创建组件.
    .参数 dwStyleEx, 整数型, , 组件扩展风格 相关常量 EOS_EX_
    .参数 lptszClassName, 整数型, , 组件类名
    .参数 lptszObjTitle, 整数型, , 组件标题
    .参数 dwStyle, 整数型, , 组件风格 相关常量 EOS_
    .参数 x, 整数型, , 左边
    .参数 y, 整数型, , 顶边
    .参数 width, 整数型, , 宽度
    .参数 height, 整数型, , 高度
    .参数 hParent, 整数型, , 父组件句柄
    .参数 nID, 整数型
    .参数 dwTextFormat, 整数型, , 相关常量 DT_
    .参数 lParam, 整数型, , 附加参数
    .参数 hTheme, 整数型, , 主题句柄.0为默认
    .参数 lpfnMsgProc, 整数型, , (BOOL)MsgProc(hWnd,hObj,uMsg,wParam,lParam,lpReturn).
```

---

### Parameters / 参数

`dwStyleEx`

Type: **DWORD**

组件扩展风格 相关常量 #EOS_EX_

`lptszClassName`

Type: **LPCWSTR**

组件类名，不同的类名决定了创建不同的组件，详情请看 Exapmle

`lptszObjTitle`

Type: **LPCWSTR**

组件标题

`dwStyle`

Type: **DWORD**

组件风格 相关常量 #EOS_

`x`

Type: **int**

左边

`y`

Type: **int**

顶边

`width`

Type: **int**

宽度

`height`

Type: **int**

高度

`hParent`

Type: **HWND**

父组件句柄

`nID`

Type: **int**

,

`dwTextFormat`

Type: **DWORD**

相关常量 #DT_

`lParam`

Type: **LPARAM**

附加参数

`hTheme`

Type: **HWND**

主题句柄.0为默认

`lpfnMsgProc`

Type: **int**

---

### Return Value / 返回值

Type: HWND

返回创建的组件句柄

### Example / 使用样例

**易语言**

（部分代码）

注意：`m_hExDui` 为 `Ex_DUIBindWindow()` 的返回结果（[点我了解绑定窗口](./Ex_DUIBindWindow.md)）

`bin`, `wzText` 都为字节集类型局部变量

`hObj`为整数型局部变量

以下代码要在绑定引擎之后、显示窗口之前使用。

```Elang

' 创建标题为“哈喽你好我是普通按钮”的按钮
bin ＝ A2W (“Button”)
wzText ＝ A2W (“哈喽你好我是普通按钮”)
hObj ＝ Ex_ObjCreateEx (-1, 取指针_字节集型 (bin), 取指针_字节集型 (wzText), -1, 50, 50, 150, 50, m_hExDui, 10001, -1, 0, 0, 0)

' 创建编辑框
bin ＝ A2W (“Edit”)
wzText ＝ A2W (“我是一个很普通的编辑框”)
hObj ＝ Ex_ObjCreateEx (-1, 取指针_字节集型 (bin), 取指针_字节集型 (wzText), -1, 25, 40, 250, 25, m_hExDui, 101, -1, 0, 0, 0)
wzText ＝ A2W (“而我是密码编辑框”)
hObj ＝ Ex_ObjCreateEx (-1, 取指针_字节集型 (bin), 取指针_字节集型 (wzText), 位或 (#EOS_VISIBLE, #编辑框风格_密码输入), 25, 70, 250, 25, m_hExDui, 102, -1, 0, 0, 0)

```

---

### References / 参考

[[1] About-Window-Classes](https://docs.microsoft.com/en-us/windows/win32/winmsg/about-window-classes)
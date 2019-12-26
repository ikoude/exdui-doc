---
description: Ex_获取资源文件Atom
---

### Syntax / 函数原型

```C++
bool __stdcall 
Ex_ResGetFileFromAtom (
    HRESOURCE hRes,
    int       atomPath,
    LPVOID    lpFile,
    DWORD*    dwFileLen
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ResGetFileFromAtom, 逻辑型, "libexdui.dll", "Ex_ResGetFileFromAtom", 公开,
    .参数 hRes, 整数型,  , 
    .参数 atomPath, 整数型,  , 
    .参数 lpFile, 整数型, 传址 ,
    .参数 dwFileLen, 整数型, 传址 ,
```

---

### Parameters / 参数

`hRes`

Type: **HRESOURCE**

资源包句柄

`atomPath`

Type: **INT32**

文件在资源内的路径<br>
**字符串唯一原子号**

`lpFile`

Type: **LPVOID**

指向该文件数据的指针<br>
无需释放该内存

`dwFileLen`

Type: **DWORD***

文件尺寸

---

### Return Value / 返回值

Type: BOOL

获取资源文件自原子号

---
description: Ex_获取资源文件
---

### Syntax / 函数原型

```C++
void __stdcall 
Ex_ResGetFile (
    HRESOURCE hRes,
    LPCWSTR   lpwzPath,
    LPVOID    lpFile,
    DWORD*    dwFileLen
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ResGetFile, 逻辑型, "libexdui.dll", "Ex_ResGetFile", 公开, 
    .参数 hRes, 整数型,  , 
    .参数 lpwzPath, 整数型,  , 
    .参数 lpFile, 整数型, 传址 , [out]
    .参数 dwFileLen, 整数型, 传址 , [out]文件尺寸.
```

---

### Parameters / 参数

`hRes`

Type: **HRESOURCE**

资源包句柄

`lpwzPath`

Type: **LPCWSTR**

文件在资源内的路径

`lpFile`

Type: **LPVOID**

指向该文件数据的指针<br>
无需释放该内存

`dwFileLen`

Type: **DWORD***

文件尺寸

---

获取资源文件

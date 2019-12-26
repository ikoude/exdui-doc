---
description: Ex_加载资源自文件
---

### Syntax / 函数原型

```C++
HRESOURCE __stdcall 
Ex_ResLoadFromFile (
    LPCWSTR lpwzFile
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ResLoadFromFile, 整数型, "libexdui.dll", "Ex_ResLoadFromFile", 公开, 
    .参数 lpwzFile, 整数型,  , 
```

---

### Parameters / 参数

`lpwzFile`

Type: **LPCWSTR**

文件路径

---

### Return Value / 返回值

Type: HRESOURCE

从文件加载资源

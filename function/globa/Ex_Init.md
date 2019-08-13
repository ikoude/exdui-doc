Title: Ex_Init
Date: 2019-8-4 11:52:21

## 初始化引擎
> 初始化ExDirectUI引擎，初始化引擎内部的各项参数，加载默认主题、语言、鼠标指针等

### 声明
```table
动态库命令(-)   |   返回值类型(-)   |   库文件名(-)   |   参数量(-)   |   备注(-)
Ex_Init   |   逻辑型   |   libexdui.dll   |   8   |   初始化引擎
```

### 参数列表
```table
参数名(<)   |   类型(-)   |   参考(-)   |   可空（NULL）(-)   |   备注(-)
hInstance   |   整数型   |   -   |   √   |   GetModuleHandle(NULL)
dwGlobalFlags   |   整数型   |   -   |   √   |   全局标识,相关常量 :#EXGF_
hDefaultCursor   |   整数型   |   -   |   √   |   默认鼠标指针
lpszDefaultClassName   |   整数型   |   -   |   √   |   默认窗口类名
lpDefaultTheme   |   整数型   |   -   |   ×   |   默认主题包指针
dwDefaultThemeLen   |   整数型   |   -   |   ×   |   默认主题包长度
lpDefaultI18N   |   整数型   |   -   |   √   |   默认语言包指针
dwDefaultI18NLen   |   整数型   |   -   |   √   |   默认语言包长度
```

### 常量列表(EXGF)
```table
常量名   |   常量值(十六进制)   |   常量值(十进制)   |   备注
EXGF_DPI_ENABLE   |   0x0002   |   2   |   启用DPI缩放
EXGF_JS_ALL   |   0x780000   |   7864320   |   允许JS全局对象访问所有资源
EXGF_JS_FILE   |   0x80000   |   524288   |   允许JS全局对象访问文件
EXGF_JS_MEMORY   |   0x100000   |   1048576   |   允许JS全局对象访问内存
EXGF_JS_MEMORY_ALLOC   |   0x200000   |   2097152   |   允许JS全局对象申请内存
EXGF_JS_PROCESS   |   0x400000   |   4194304   |   允许JS全局对象创建进程、允许程序、加载DLL
EXGF_MENU_ALL   |   0x800000   |   8388608   |   渲染所有菜单
EXGF_OBJECT_DISABLEANIMATION   |   0x10000   |   65536   |   禁用动画效果
EXGF_OBJECT_SHOWPOSTION   |   0x40000   |   262144   |   显示组件位置
EXGF_OBJECT_SHOWRECTBORDER   |   0x20000   |   131072   |   显示组件边界
EXGF_RENDER_CANVAS_ALIAS   |   0x0040   |   64   |   画布_不抗锯齿
EXGF_RENDER_METHOD_D2D   |   0x0100   |   256   |   使用D2D渲染
EXGF_RENDER_METHOD_D2D_GDI_COMPATIBLE   |   0x0300   |   768   |   使用支持GDI交互的D2D渲染
EXGF_RENDER_METHOD_GDI   |   0x0080   |   128   |   使用GDI/GDI+渲染
```

### 使用示例
> 详见每一个例程

#### 易语言

```table
动态库命令(-)   |   参数(-)   |   数据类型(-)   |   库文件名(-)   |   在库中对命令名(-)   |   备注(-)
GetModuleHandle   |   -   |   整数型   |   kernel32   |   GetModuleHandleA   |   返回指定模块名的句柄，如果为0，则返回本模块的句柄
-   |   lpModuleName   |   整数型   |   -   |   -   |   指定模块名
```
```table
|变量名|类型(-)|静态(-)|数组(-)|备注|
|bin|字节集|×|×|声明局部变量|
```

- Ex_Init()
    - hInstance : GetModuleHandle(0)
    - dwGlobalFlags:位或(#EXGF_DPI_ENABLE, #EXGF_RENDER_METHOD_D2D, #EXGF_MENU_ALL)
    - hDefaultCursor:0
    - lpszDefaultClassName:0
    - lpDefaultTheme:取指针_字节集型 (bin),
    - dwDefaultThemeLen:取字节集长度 (bin)
    - lpDefaultI18N:0
    - dwDefaultI18NLen:0

#### C++

```c++

```
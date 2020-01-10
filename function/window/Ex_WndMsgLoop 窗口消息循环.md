---
description: 窗口消息循环。整体流程为：初始化引擎 -> 创建窗口 -> 绑定窗口 -> 设置窗口属性 -> 显示窗口 -> **消息循环** -> 销毁窗口
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_WndMsgLoop (void);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_WndMsgLoop, 整数型, "libexdui.dll", "Ex_WndMsgLoop", 公开, 
```

---

### Return Value / 返回值

Type: INT32 整数型

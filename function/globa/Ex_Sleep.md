Title: Ex_Sleep
Date: 2019年8月4日11时52分23秒

### 延时
> 暂停当前程序的运行并等待指定的时间

### 声明
```table
动态库命令(-)   |   返回值类型(-)   |   库文件名(-)   |   参数量(-)   |   备注(-)
Ex_Sleep   |   -   |   libexdui.dll   |   1   |   暂停当前程序的运行并等待指定的时间
```

### 参数列表(Ex_Sleep)
```table
参数名(<)   |   类型(-)   |   参考(-)   |   可空（NULL）(-)   |   备注(-)
us   |   整数型   |   -   |   ×   |   指定欲暂停程序执行的时间，单位为毫秒
```

### 使用示例

#### 易语言
- 输出调试文本("你好")
- Ex_Sleep(10000)
    - us:10000
- 输出调试文本("世界")

#### C++
```C++
// 省略函数声明
#include <iostream> 
using namespace std; 
int main() {
   cout << "Hello World" << endl; 
   Ex_Sleep(10000);
   Cout << ("World") << endl;
   return 0;
}
```



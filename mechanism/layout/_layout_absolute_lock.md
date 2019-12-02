Title: _layout_absolute_lock
Date: 2019年8月4日11时52分23秒

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_absolute_lock (
    int hLayout,
    int hObjChild,
    int tLeft,
    int tTop,
    int tRight,
    int tBottom,
    int tWidth,
    int tHeight
);
```

### Parameters / 参数

`hLayout`

Type: **HANDLE**

`hObjChild`

Type: **HANDLE**

`tLeft`

Type: **INT32**

请参阅下方 ELCP_ABSOLUTE_*XXX*_TYPE

`tTop`

Type: **INT32**

请参阅下方 ELCP_ABSOLUTE_*XXX*_TYPE

`tRight`

Type: **INT32**

请参阅下方 ELCP_ABSOLUTE_*XXX*_TYPE

`tBottom`

Type: **INT32**

请参阅下方 ELCP_ABSOLUTE_*XXX*_TYPE

`tWidth`

Type: **INT32**

请参阅下方 ELCP_ABSOLUTE_*XXX*_TYPE

`tHeight`

Type: **INT32**

请参阅下方 ELCP_ABSOLUTE_*XXX*_TYPE

---

##### 易语言声明
```Elang
.DLL命令 _layout_absolute_lock, 逻辑型, "libexdui.dll", "_layout_absolute_lock", 公开, 按当前位置锁定
    .参数 hLayout, 整数型,  , 
    .参数 hObjChild, 整数型,  , 
    .参数 tLeft, 整数型,  ,
    .参数 tTop, 整数型,  , 
    .参数 tRight, 整数型,  , 
    .参数 tBottom, 整数型,  , 
    .参数 tWidth, 整数型,  , 
    .参数 tHeight, 整数型,  , 
```

---

##### ELCP_ABSOLUTE_XXX_TYPE
| Value                        | Meaning  |
| --                           | --  |
| ELCP_ABSOLUTE_TOP_TYPE       | 布局属性_绝对_顶部类型  |
| ELCP_ABSOLUTE_RIGHT_TYPE     | 布局属性_绝对_右侧类型  |
| ELCP_ABSOLUTE_BOTTOM_TYPE    | 布局属性_绝对_底部类型  |
| ELCP_ABSOLUTE_WIDTH_TYPE     | 布局属性_绝对_宽度类型  |
| ELCP_ABSOLUTE_HEIGHT_TYPE    | 布局属性_绝对_高度类型  |
| ELCP_ABSOLUTE_OFFSET_H_TYPE  | 布局属性_绝对_水平偏移量类型  |
| ELCP_ABSOLUTE_OFFSET_V_TYPE  | 布局属性_绝对_垂直偏移量类型  |

---


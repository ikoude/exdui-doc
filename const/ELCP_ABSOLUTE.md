##### ExDirectUI Layout

---

### ELCP_ABSOLUTE_XXX

| Name                         | Value  | Meaning  |
| --                           | --     | --       |
| ELCP_ABSOLUTE_LEFT           | 0x01   | 布局属性\_绝对\_左侧  |
| ELCP_ABSOLUTE_TOP            | 0x03   | 布局属性\_绝对\_顶部  |
| ELCP_ABSOLUTE_RIGHT          | 0x05   | 布局属性\_绝对\_右侧  |
| ELCP_ABSOLUTE_BOTTOM         | 0x07   | 布局属性\_绝对\_底部  |
| ELCP_ABSOLUTE_WIDTH          | 0x09   | 布局属性\_绝对\_宽度<br>优先级低于右侧  |
| ELCP_ABSOLUTE_HEIGHT         | 0x0B   | 布局属性\_绝对\_高度<br>优先级低于底部  |


### ELCP_ABSOLUTE_XXX_TYPE

| Name                         | Value  | Meaning  |
| --                           | --     | --       |
| ELCP_ABSOLUTE_TOP_TYPE       | 0x04   | 布局属性\_绝对\_顶部类型  |
| ELCP_ABSOLUTE_RIGHT_TYPE     | 0x06   | 布局属性\_绝对\_右侧类型  |
| ELCP_ABSOLUTE_BOTTOM_TYPE    | 0x08   | 布局属性\_绝对\_底部类型  |
| ELCP_ABSOLUTE_WIDTH_TYPE     | 0x10   | 布局属性\_绝对\_宽度类型  |
| ELCP_ABSOLUTE_HEIGHT_TYPE    | 0x12   | 布局属性\_绝对\_高度类型  |
| ELCP_ABSOLUTE_OFFSET_H_TYPE  | 0x14   | 布局属性\_绝对\_水平偏移量类型  |
| ELCP_ABSOLUTE_OFFSET_V_TYPE  | 0x16   | 布局属性\_绝对\_垂直偏移量类型  |


### ELCP_ABSOLUTE_XXX_XXX

| Name                         | Value  | Meaning  |
| --                           | --     | --       |
| ELCP_ABSOLUTE_OFFSET_H       | 0x0D   | 布局属性\_绝对\_水平偏移量  |
| ELCP_ABSOLUTE_OFFSET_V       | 0x0F   | 布局属性\_绝对\_垂直偏移量  |
| ELCP_ABSOLUTE_TYPE_UNKNOWN   | 0x00   | 布局属性\_绝对\_类型\_未知<br>未设置或保持不变  |
| ELCP_ABSOLUTE_TYPE_PX        | 0x01   | 布局属性\_绝对\_类型\_像素  |
| ELCP_ABSOLUTE_TYPE_PS        | 0x02   | 布局属性\_绝对\_类型\_百分比  |
| ELCP_ABSOLUTE_TYPE_OBJPS     | 0x03   | 布局属性\_绝对\_类型\_组件尺寸百分比<br>仅OFFSET可用  |

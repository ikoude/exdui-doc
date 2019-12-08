##### ExDirectUI Global Flag

---

| Name                                  | Value     | Meaning  |
| --                                    | --        | --       |
| EXGF_DPI_ENABLE                       | 0x02      | 启用DPI缩放  |
| EXGF_RENDER_CANVAS_ALIAS              | 0x40      | 画布_不抗锯齿  |
| EXGF_RENDER_METHOD_GDI                | 0x80      | 使用GDI/GDI+渲染  |
| EXGF_RENDER_METHOD_D2D                | 0x0100    | 使用D2D渲染  |
| EXGF_RENDER_METHOD_D2D_GDI_COMPATIBLE | 0x0300    | 使用支持GDI交互的D2D渲染  |
| EXGF_OBJECT_DISABLEANIMATION          | 0x010000  | 禁用动画效果  |
| EXGF_OBJECT_SHOWRECTBORDER            | 0x020000  | 显示组件边界  |
| EXGF_OBJECT_SHOWPOSTION               | 0x040000  | 显示组件位置  |
| EXGF_JS_FILE                          | 0x080000  | 允许JS全局对象访问文件  |
| EXGF_JS_MEMORY                        | 0x100000  | 允许JS全局对象访问内存  |
| EXGF_JS_MEMORY_ALLOC                  | 0x200000  | 允许JS全局对象申请内存  |
| EXGF_JS_PROCESS                       | 0x400000  | 允许JS全局对象创建进程、允许程序、加载DLL  |
| EXGF_JS_ALL                           | 0x780000  | 允许JS全局对象访问所有资源  |
| EXGF_MENU_ALL                         | 0x800000  | 渲染所有菜单  |

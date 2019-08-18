# 常量列表
|常量名称|常量值(十六进制)|常量值(十进制)|备注|
|----|----|----|----||----|
|TVM_DELETEITEM|1101|4353|删除节点及所有子孙(lParam为节点句柄|
|TVM_ENSUREVISIBLE|1114|4372|保证显示(lParam为显示的节点句柄)|
|TVM_EXPAND|1102|4354|展开收缩(wParam为是否展开|
|TVM_GETCOUNT|1105|4357|取节点数|
|TVM_GETINDENT|1106|4358|取留白宽度|
|TVM_GETITEMW|113E|4414|取节点信息(wParam为节点句柄|
|TVM_GETITEMRECT|1104|4356|取节点矩形(wParam为节点句柄|
|TVM_GETNEXTITEM|110A|4362|取相关节点(wParam为TVGN_开头的常量|
|TVM_GETVISIBLECOUNT|1110|4368|取展开可视节点个数|
|TVM_HITTEST|1111|4369|命中测试(wParam低位为x高位为y[相对控件]|
|TVM_INSERTITEMW|1132|4402|插入节点(lParam为EX_TREEVIEW_ITEMINFO指针，tzText为Unicode)|
|TVM_SELECTITEM|110B|4363|置选中项(lParam为选中的节点句柄)|
|TVM_SETINDENT|1107|4359|设置留白宽度(wParam为留白宽度)|
|TVM_SETITEMW|113F|4415|设置节点标题(wParam为节点句柄|
|TVM_UPDATE|1193|4499|更新树形框|
|TVM_SETITEMHEIGHT|13E3|5091|设置行高(lParam为新行高)|
|TVM_GETITEMHEIGHT|13E4|5092|获取行高|
|TVM_GETNODEFROMINDEX|13E5|5093|从索引获取节点句柄(wParam为索引|


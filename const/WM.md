# 常量列表
|常量名称|常量值(十六进制)|常量值(十进制)|备注|
|----|:--:|:--:|:--:|
|WM_CHAR|102|258|按下某键，并已发出WM_KEYDOWN，WM_KEYUP消息|
|WM_MOVE|3|3|移动一个窗口|
|WM_SIZE|5|5|改变一个窗口的大小|
|WM_CLOSE|10|16|当一个窗口或应用程序要关闭时发送一个信号|
|WM_DESTROY|2|2|一个窗口被销毁|
|WM_CREATE|1|1|应用程序创建一个窗口|
|WM_COMMAND|111|273|当用户选择一条菜单命令项或当某个控件发送一条消息给它的父窗口，一个快捷键被翻译|
|WM_NOTIFY|4E|78|当某个控件的某个事件已经发生或这个控件需要得到一些信息时，发送此消息给它的父窗口|
|WM_KEYUP|101|257|释放一个键|
|WM_KEYDOWN|100|256|按下一个键|
|WM_MOUSEMOVE|200|512|移动鼠标|
|WM_LBUTTONUP|202|514|释放鼠标左键|
|WM_LBUTTONDOWN|201|513|按下鼠标左键|
|WM_LBUTTONDBLCLK|203|515|双击鼠标左键|
|WM_RBUTTONDOWN|204|516|按下鼠标右键|
|WM_RBUTTONUP|205|517|释放鼠标右键|
|WM_ACTIVATE|6|6|一个窗口被激活或失去激活状态；|
|WM_SETFOCUS|7|7|获得焦点后|
|WM_HSCROLL|114|276|当一个窗口标准水平滚动条产生一个滚动事件时发送此消息给那个窗口，也发送给拥有它的控件|
|WM_VSCROLL|115|277|当用户已经登入或退出后发送此消息给所有的窗口，当用户登入或退出时系统更新用户的具体|
|WM_PAINT|F|15|要求一个窗口重画自己|
|WM_NCHITTEST|84|132|命中测试|
|WM_DROPFILES|233|563|收到拖拽文件|
|WM_TIMER|113|275|时钟|
|WM_KILLFOCUS|8|8|失去焦点|
|WM_MOUSEHOVER|2A1|673|鼠标移入|
|WM_MOUSELEAVE|2A3|675|鼠标移出|
|WM_MOUSEWHEEL|20A|522|当鼠标轮子转动时发送此消息个当前有焦点的控件|

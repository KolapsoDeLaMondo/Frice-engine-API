## 类Game ##

---
生命周期方法||
-------|-------|
protected open fun onInit(): Unit|在被初始化时调用|
protected open fun onExit(): Unit|在退出时调用（注：引擎不会自己退出进程） |
protected open fun onRefresh(): Unit| （非暂停时）对游戏窗口进行刷新|
protected open fun onClick(e: OnClickEvent): Unit|点击窗口时调用|
protected open fun onMouse(e: OnMouseEvent): Unit|发生鼠标事件是产生（如移动指针，点击按键）|
protected open fun onLoseFocus(e: OnWindowEvent?): Unit||
protected open fun onFocus(e: OnWindowEvent?): Unit|在游戏窗口获得焦点时触发|




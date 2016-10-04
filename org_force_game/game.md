## 类Game ##

---
生命周期方法||
-----|-----|
protected open fun onInit(): Unit|在被初始化时调用|
protected open fun onExit(): Unit|在退出时调用（注：引擎不会自己退出进程） |
protected open fun onRefresh(): Unit| （非暂停时）对游戏窗口进行刷新|
protected open fun onClick(e: OnClickEvent): Unit||


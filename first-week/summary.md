###自定义网页右键菜单
####效果
* 鼠标右击时，出现自定义菜单。点击非自定义菜单区域时，隐藏自定义菜单
* 点击自定义菜单条目时，弹出菜单条目名称

####页面已实现
* 自定义菜单出现在鼠标指针右下方，当右边区域不够大，展示在左下方，当下方区域不够时，展示在鼠标指针上方
* 屏蔽原来右击菜单(oncontextmenu事件中return false)
* 在点击自定义菜单时，阻止事件冒泡（event.stopPropagation()）
* 随浏览器窗口宽度变化而变化

仍存在的问题 滚动条时处理 IE8兼容
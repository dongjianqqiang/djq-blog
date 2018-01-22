swiper 坑
    1. swiper 轮播图初始化渲染元素不能隐藏，如果隐藏将会渲染不正常。
    2. 关于图片大图预览  swiper 如果是循环模式的话，索引不会从第一个开始，所以大图弹框是预览 用silderTo 放直接索引加 5 跳过去。

iframe 父子页面操作
    1、HTML语法：<iframe name="myFrame" src="child.html"></iframe> 
    2、父窗口调用子窗口：myFrame.window.functionName(); 
    3、子窗品调用父窗口：parent.functionName(); 
    简单地说,也就是在子窗口中调用的变量或函数前加个parent.就行 

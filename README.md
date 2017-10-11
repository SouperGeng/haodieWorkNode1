# haodieWorkNode1
- 同步异步区别：同步阻塞模式，如果该进程需要请求一段时间才会返回结果，那其他进程会继续等待。异步非阻塞模式，如果该进程需要请求一段时间返回结果，那么其他进程会继续进行，该进程不会影响其他进程状态。
- 跨域请求的方法：1、jsonp（动态创建script标签）2、document.domain+iframe 3、window.name 、window.postMessage 4、服务器上设置代理页面
- 阻止事件冒泡：event.stopPropagation()\ie浏览器：event.cancelBubble=true;
- 哪些操作会造成内存泄漏：1、闭包；2、setTimeout的第一个参数是字符串而非函数时，会造成内存泄漏；3、循环（两个对象彼此引用，且彼此保留时）；

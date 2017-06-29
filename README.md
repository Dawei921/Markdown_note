补充：
发送jsonp的请求:this.$http.jsonp(url,{params:{}}).then(function(resp){},function(resp){});
生命周期：
  init: 实例开始初始化
  created：实例已经被创建
  beforeCompile:编译之前
  compiled:编译之后
  ready: 准备就绪，插入文档中，此时页面中才是真正显示内容
  beforeDestroy:销毁之前
  destroyed: 销毁之后
手动销毁：this.$destroy() 内置方法

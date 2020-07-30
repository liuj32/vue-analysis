# Vue

## vscode在js文件不能识别flow语法？
参考：https://blog.csdn.net/ckwang6/article/details/88625452

## new Vue发什么了什么？
mountComponent() => vm._update(vm._render(), hyrating)
  vm._render() => render.call(vm._renderProxy, vm.$createElement) //vm.$createElement => vnode
  vm._update() => vm.__patch__() => dom //__patch__将vdom转化为dom
  
* virtual Dom
参考：snabbdom

总结：new Vue => init => $mount =>  compile => render => vnode => patch => Dom


## 组件化
* createComponent()
  3个核心步骤： 构造子类构造函数 -> 安装组件钩子函数 -> 实例化vnode

* patch

* 合并配置
  
* 生命周期
  
* 组件注册
  

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











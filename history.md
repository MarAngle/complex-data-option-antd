### 2.1.0
- 版本逻辑更新，非兼容更新将会在第二位表现

### 2.0.6
- 依赖固定版本号

### 2.0.5
- 删除currentDate相关，使用complex-func的current相关
- index更改

### 2.0.4
- info相关的设置通过option暴露初始设置值,list会暴露到跟节点，edit可通过extra传递
- complex-func的引用从Vue原型链引用改为import引用，避免挂载属性设置非默认的情况
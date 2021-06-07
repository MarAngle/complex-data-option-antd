### 2.0.5ing
- 删除currentDate相关，使用complex-func的current相关

### 2.0.4
- info相关的设置通过option暴露初始设置值,list会暴露到跟节点，edit可通过extra传递
- complex-func的引用从Vue原型链引用改为import引用，避免挂载属性设置非默认的情况
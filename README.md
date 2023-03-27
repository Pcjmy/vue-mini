# README

vue-mini

- 响应系统
- runtime 运行时
- compiler 编译器

## 响应系统

对于`reactive`的响应性函数而言

- 通过`proxy`的`setter`和`getter`来实现的数据监听
- 需要配合`effect`函数进行使用
- 基于`WeakMap`完成的依赖收集和处理

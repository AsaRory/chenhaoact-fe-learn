# js dom 常用方法与属性整理

项目中经常用到的单另再整理一份放在这里。

## 属性

## 方法
document.querySelector\(_CSS selectors_\) 返回文档中匹配指定 CSS 选择器的一个元素。

document.createElement\(name\)  创建元素节点（这里的name是某种html标签类型名称如div）。此方法可返回一个 Element 对象。

document.createElementNS \(ns,name\)  可创建带有指定命名空间的元素节点。此方法可返回一个 Element 对象。

setAttribute\(_attributename,attributevalue_\)  添加指定的属性，并为其赋指定的值。如果这个指定的属性已存在，则仅设置/更改值。

appendChild\(node\)  向节点添加最后一个子节点。


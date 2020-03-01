# jtopo 

感谢 jtopo 原作者，这个版本的 JTopo 跟原版（0.48.1）的区别不大。

jtopo 官网地址： http://www.jtopo.com/

jtopo 交流群：171820448

此 npm 包使用 demo：https://github.com/heyi-let/OpenSource-demo/tree/master/jtopo-in-node-demo

## 说明

此代码主要来源于 jtopo 交流群的群友低调做人（S_Autumn/20978252）上传的群文件，经过群友 let、修改而成。

## 修改

S_Autumn 2015.7.24 修改：

- 修正了一些 BUG、顺手写了一些注释方便阅读
- 另外主要扩展了图形自动化布局、节点支持多位置换行文本，并且重新实现序列化和反序列化
- 其中图形自动化布局是依托于springy.js(已整合)它，是开源的实现弹力模型的一个js

S_Autumn 2015.8.01 修改：

- 修正序列化、反序列化  
- 修正丢失图片问题
			

let、 2018/03/12 修改:

- 修改 jtopo 导出方式以便支持模块化导入
- 移除对 jquery 的依赖（主要是 $.extend）


let、 2019/01/14 修改:

- 修改为一个 npm 包，方便模块化项目引用。
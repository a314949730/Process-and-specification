###  前端开发流程以及规范

##### 当前的问题
每个人的代码风格不一样
组件库和框架不统一
es6新特性运用,开发效率提示（变量，模板字符串，箭头函数，函数默认参数，对象和数组解构，for..of, for..in， 类，超类）
scss （变量,混合mixin,继承@extend,操作符,函数）

#### 规范化、模块化、组件化、自动化
1. ##### 规范化
** vscode 工具配置**
ESlint //js代码规范
HTMLHint  //html 代码检测
stylelint //css样式检测
Prettier - Code formatter  //代码格式化工具
path intellisense  //自动路径补全
Document this //js模板注释

[命名规范](https://devcloud.huaweicloud.com/docman/project/7158ffc402e84ef3b48d657b365cf235/docman/detail/2854238/list)

[css代码规范](https://devcloud.huaweicloud.com/docman/project/7158ffc402e84ef3b48d657b365cf235/docman/detail/2854236/list)

[js代码规范](https://devcloud.huaweicloud.com/docman/project/7158ffc402e84ef3b48d657b365cf235/docman/detail/2854237/list)

2. #### 模块化
[ES6](https://juejin.im/post/5ca0df406fb9a05e444f2bed)
模块内定义的变量不会被自动添加到全局作用域
模块要向外面暴露一些自己的数据, 这些数据可以被外界访问到
一个模块可以从另外一个模块中导入数据(即可以使用其他模块的数据)
模块顶层的 `this` 是 `undefined`, 并不是 `window` 或 `global`

3. #### 组件化
**基础组件**（排版,表单）
**工具类**(日期格式化，数组的操作排序，对象的遍历，axios的二次封装，常用的正则匹配验证)
**业务组件**（直播组件，详情页组件，播放列表）

4. #### 自动化
Sentry（产生报错的日志收集）

WebPagetest（性能测试）

Jest（组件单元测试），

jenkins（自动化部署）




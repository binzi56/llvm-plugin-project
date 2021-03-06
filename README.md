# llvm-plugin-project


## 自定义插件汇总

### [clang-checkCode](./Plugins/clang-checkCode)
>  代码规范检查插件

检测项说明:
- 检测类名是否存在小写开头
- 检测类名是否包含下划线
- 检测方法名是否存在大写开头
- 检测方法中定义的参数名称是否存在大写开头
- 检测方法实现是否超过1000行代码
- 检测属性名是否存在大写开头
- 检测属性名是否包含下划线
- 检测委托属性是否有使用weak修饰
- 检测常量名称是否存在小写开头
- 检测变量名称是否存在大写开头

效果图部分展示:

![clang-checkCode效果图](./Resources/clang-checkCode.png)


### [Drafter](https://github.com/L-Zephyr/Drafter)
>  代码函数调用关系图(支持Objective-C和Swift)

基本使用说明:
- 导出HTML在浏览器中查看
   - 函数调用关系(Call Graph)
   - 类继承关系(Class Diagram)
- 导出为PNG

效果图部分展示:

![Drafter效果图](./Resources/Drafter.png)

### [XcodeZombieCode](https://github.com/kangwang1988/XcodeZombieCode)
> 无用代码/重复代码分析



### 文档整理
* [Clang 12 documentation](http://clang.llvm.org/docs/index.html)
* [cplusplus reference](http://www.cplusplus.com/reference/)
* [深入剖析 iOS 编译 Clang LLVM](https://github.com/ming1016/study/wiki/深入剖析-iOS-编译-Clang---LLVM)
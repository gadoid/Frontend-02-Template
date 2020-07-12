学习笔记

* 形式语言
  * 0型 无限制文法
    * ？::=？
  * 1型 上下文相关文法
    * ?<a>?:=?<b>?
  * 2型 上下文无关文法
    * <a>::=?
  * 3型 正则文法
    * <a>::<a>?
    * <a>::=?<a> 不能出现在末尾
  * 上下包含
* 产生式
  * BNF
  * 尖括号 表示语法结构名
  * 语法结构分成基础结构和需要用其他语法结构定义的复合结构
    * 基础结构称终结符
    * 复合结构称非终结符
  * 引号和中间的字符表示终结符
  * 可以有括号
  * * 表示重复多次
  * |表示或
  * + 表示至少一次
  * ：：= 表示被定义为
  * []内容为可选项
  * {}内容为可重复0至无限次的项
* 形式语言
  * 0型 无限制文法
    * ？::=？
  * 1型 上下文相关文法
    * ?<a>?:=?<b>?
  * 2型 上下文无关文法
    * <a>::=?
  * 3型 正则文法
    * <a>::<a>?
    * <a>::=?<a> 不能出现在末尾
  * 上下包含
* 产生式
  * BNF
  * 尖括号 表示语法结构名
  * 语法结构分成基础结构和需要用其他语法结构定义的复合结构
    * 基础结构称终结符
    * 复合结构称非终结符
  * 引号和中间的字符表示终结符
  * 可以有括号
  * * 表示重复多次
  * |表示或
  * + 表示至少一次
  * ：：= 表示被定义为
  * []内容为可选项
  * {}内容为可重复0至无限次的项
* 语言分类
  * 数据描述语言
    * JSON HTML XAML SQL CSS
  * 编程语言
    * C、C++、Java、C#、Python，Ruby
  * 声明式语言
    * JSON HTML XAML SQL CSS Lisp
  * 命令型语言
    * C、C++、Java、C#、Python
* 图灵完备性
  * 图灵完备：
    * 在[可计算性理论](https://baike.baidu.com/item/%E5%8F%AF%E8%AE%A1%E7%AE%97%E6%80%A7%E7%90%86%E8%AE%BA/2125738)里，如果一系列操作数据的规则（如[指令集](https://baike.baidu.com/item/%E6%8C%87%E4%BB%A4%E9%9B%86/238130)、[编程语言](https://baike.baidu.com/item/%E7%BC%96%E7%A8%8B%E8%AF%AD%E8%A8%80/9845131)、[细胞自动机](https://baike.baidu.com/item/%E7%BB%86%E8%83%9E%E8%87%AA%E5%8A%A8%E6%9C%BA/2765689)）可以用来模拟单带图灵机，那么它是**图灵完备的**。这个词源于引入图灵机概念的数学家[艾伦·图灵](https://baike.baidu.com/item/%E8%89%BE%E4%BC%A6%C2%B7%E5%9B%BE%E7%81%B5)。在[可计算性理论](https://baike.baidu.com/item/%E5%8F%AF%E8%AE%A1%E7%AE%97%E6%80%A7%E7%90%86%E8%AE%BA/2125738)里，如果一系列操作数据的规则（如[指令集](https://baike.baidu.com/item/%E6%8C%87%E4%BB%A4%E9%9B%86/238130)、[编程语言](https://baike.baidu.com/item/%E7%BC%96%E7%A8%8B%E8%AF%AD%E8%A8%80/9845131)、[细胞自动机](https://baike.baidu.com/item/%E7%BB%86%E8%83%9E%E8%87%AA%E5%8A%A8%E6%9C%BA/2765689)）可以用来模拟单带图灵机，那么它是**图灵完备的**。这个词源于引入图灵机概念的数学家[艾伦·图灵](https://baike.baidu.com/item/%E8%89%BE%E4%BC%A6%C2%B7%E5%9B%BE%E7%81%B5)。
  * 实现方式
    * 命令式——图灵机
      * goto
      * if /while
    * 声明式
      * lambda
      * 使用递归方式实现图灵完备
* 动态/静态语言
  * 通过判断组织类型的位置来判断是动态还是静态
    * 动态
      * 在用户的设备、在线服务器上
      * 产品实际运行时
      * Runtime
    * 静态
      * 在开发设备上
      * Complietime
* 语言设计方式
  * Atom —— Expression —— Statement —— Structure —— Program
  * Atom
    * 变量声明
  * Expression
    * 表达式
  * Statement
    * 代码块
  * Structure
    * 代码结构 类、函数、进程、命名空间
  * Program
    * 程序 Module（准备复用的模块） 、Program（实际执行的项目）
* JavaScript基本类型
  * number
  * string
  * Boolean
  * Null
  * Undefine
  * Object
  * Symbol
  *

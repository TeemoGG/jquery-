Jquery框架：
1、js对象和jquery对象的区别
2、js对象和jquery对象的转换
3、核心方法
4、选择器
5、筛选
6、属性选择器
7、文档处理
8、css处理
9、事件
10、效果
11、ajax无刷新
12、工具

 
js 对象和jquery对象的区别：
jquery 就是js中的new Object生成的普通对象
 
js 对象和jquery对象的方法能不能共用？  不能共用
 
js 对象和jquery 对象能不能互换？  能
1、js对象->jquery对象
$(dom)
2、js对象->jquery对象
$('selector').[index]
$('selector').get(1)
 
核心 方法
each();
size();
length;
get();
get(index);
index(); 搜索匹配的元素
data();

 
选择器：
1、基础  
  1)#id 
  2)ele 
  3).class 
  4)* 
  5)sell,sel2
2、层级  
  1)ancestor  descendant
  2)parent >child
  3)prev + next
  4)prev~siblings 
3、基本
  1):first
  2):last
  3):not
  4):even
  5):odd
  6):eq
  7):gt  大于
  8):lt  小于
4、内容
 1):has
 2):parent
 3):enpty
5、属性
  1)[name]
  2)[name=user1]
  3)[name!=user1]
  4)[name^=user]
  5)[name$=user]
  6)[name*=er]
  7)[name=user1][name*=er]
6、子元素
  1)nth-child
  2)first-child
  3)last-child
  4)only-child
7、表单
  1):input
  2):text
  3):password
  4):radio
  5):checkbox
  6):submit
  7):reset
  8):button
  9):file
  10):hidden
8、表单属性
  1):checked
  2):selected
  
 
 筛选：
 1、过滤
 eq()
 first()
 last()
 not()
 slice()
 
 2、查找
 children()
 find()
 next()
 nextAll()
 parent()
 prev()
 prevAll()
 siblings()
 
 3、串联
 add()
 andSelf()
 
 属性：
 1、属性
 attr()
 attr({})
 
 2、css类
 addClass()
 removeClass()
 toggleClass()
 
 3、HTML代码
 html() 取值
 html(val)  赋值
 
 4、文本
 text()
 text(val)
 
 5、值
 val()取值
 val(val)赋值
 
 文档处理
 1、内部插入
 append（）
 appendTo（）
 prepend()
 prependTo()
 
 2、外部插入
after()
before()
insertAfter()

3、包围

 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

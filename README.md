# css笔记
# 内部样式表
>1. 《style》 选择器{样式} 《/style》
>2. 标签名 style="属性"
# 外部样式
* 引入文件
>1. 《link rel="stulesheet" type="text/css" href="css入径"》
# 类选择器
>1. color 颜色
>2. font-size 字体大小
>3. class="one" 选择器 .one
>4. id="two" 选择器 #two
>5. 多类名 class="one two"
# css样式属性
* 字体
>1. font-size:50px; 字体大小
>2. font-style 倾斜 em i
>3. font-weight 字体加粗 bold 700 normal 400 不加粗 bolder 特粗体  lighter 细体
>4. font-family 字体
* font 综合写法
>1. font:斜体 加粗 字号/行高 字体; 
>2. 字号和行高一定不能省略
* 文本
>1. color 颜色 十六进制必须#开头
>2. line-height 行高
>3. text-indent 首行缩进 2em 相当于两个字
>4. text-align 盒子里面的文本居中对齐
>5. text-decroation 文本修饰
>6. none 取消下划线 nuderline 添加下划线
* 复合选择器
>1. 后代选择器 .类名 标签 标签
>2. 子元素选择器 类名(标签)>标签(类名)
>3. 交集选择器 标签名 . 类名
>4. 并集选择器 标签名，标签名，类名
* 链接伪类
>1. a:link{} 未被访问过的链接 
>2. a:visited{} 被访问过的链接
>3. a:hover{} 鼠标经过连接
>4. a:active{} 点击鼠标没有放开的时候
* 块状元素
>1. h1-h6 div p ul ol li 等
* 特点
>1. 高度，宽度，外边距，内边距都可以控制
>2. 宽度默认为容器的100%
>3. 是一个容器及盒子，里面可以放行内元素或者块状元素
>* 注意
>1. 只有文字才有段落 因此 p 里面不能放块级元素，特别p不能放dv
>2. 同理还有这些标签h1-h6。dt，他们都是文字类块级标签，里面不能放其他块状元素
* 行内元素
>1. 常见的行内元素 a b strong em i del
s ins u span 等 
>2. 一行可以显示多个
>3. 不能控制高度，宽度
>4. 宽度跟内容有关
>5. 行内元素 只能放行内元素和文本
>* 注意
>1. 链接里不能放链接
>2. 链接里可以放入块状元素 ，但是a链接转换成块状元素更安全
* 行内块元素
>1. img input td
* 样式转换
>1. 块状转行内 display:inline;
>2. 行内传块  display:block;
>3. 转换成行内块 diaolay:inline-block;
* 背景颜色
>1. background-color 插入背景颜色
>2. background-image:url() 插入背景图片
>3. no-repeat 不平铺
* 背景位置
>1. background-position x坐标 y坐标
>2. right 右 left 左 top 上 bottom 下 center 中
>3. background-attachment:fixed 背景固定 croll 跟随滚动
* 简写
>1. background:颜色 url() no-repeat fixed center top  
* 透明度
>1. backround:rgba(0,0,0,0.5)
* css层叠性
>1. 就近原则
>2. 没有冲突的不会出现覆盖性
* 继承性
>1. 可以减轻代码的复杂性
>2. 只能继承父元素的个别属性（text-，font-，line-，以及color）
* 优先级
>1. 选择器不同 通过计算权重公式决定优先级
>2. !important 在样式后面添加 无穷大  最大
* 边框
>1. broder-style:solid 实线
>2. broder-style:dashed 虚线
>3. broder-style:dotted 点线
>4. 简写 broder: 1px solid 颜色
>5. broder-collapse:collapse 合并重叠相邻的边框
* 内边距 padding(爬 订)
>1. padding 上下内边距 左右外边距
>2. padding 上下边距 左右边距 下边距
>3. padding 上内边距 又内边距 下内边距 左边距
1，HTML4，HTML5，CSS2，CSS3？
    HTML是一个系列：HTML1，HTML2，HTML3，HTML4，HTML5，HTML6
        核心：标签
        在HTML5这个版本中添加的不仅仅是标签，还添加了其它内容。
            如： header, footer, nav, section。
                数据存储，地图......
    CSS也是一个系列：CSS1, CSS2, CSS3
        CSS1已经淘汰了
        主流是CSS2和CSS3， 简称为C2和C3。

        C2：核心是就是一堆的属性和一些基本的选择器。
            选择器：p id class 后代 分组 * 交集  伪类
            属性：文本，字体，盒子，定位，列表，表格
        
        C3：在C3中肯定增加了很多选择器，和很多属性。
            选择器添加了80个左右。
            属性添加了20个左右。  有三个非常牛比的属性。 通常把这三个属性叫C3中的三大核心模块。
            flex
            媒体查询

        今天我们主要讲CSS3中的三个非常牛比的属性。可以用来写动画。

2，HTML5和CSS3有什么关系？
    没有是关系。是不同的技术。

3，CSS3是有兼容性的问题？
    对于H5，C3兼容性问题，刚开始不用管。
    兼容性后面专门去讲。现在不需要管它。

4，先学习几个选择器？
    属性选择器 input[title]
    关系选择器 div span       div>span 
    伪类选择器 :root :nth-child :fist-child :last-child  :nth-last-child

文档-->html文档  根标签是<html></html>

5，CSS3中的三大核心模块？  这三大核心模块是用来写动画的，或特效。
    过渡动画
    变形
    自定义动画

5，过渡动画？
    transition  本意：过渡，转变，变迁
    作用：在发生突变的属性上，发生过渡动画
    格式：transition: 要发生变化的属性名 动画时长 缓冲曲线 等待时间
            transition-property: 要发生变化的属性名
            transition-duration: 动画时长 
            transition-timing-funciton: 缓冲曲线
            transition-delay：等待时间

6,书写过渡动画的步骤？
    1，按照以往形式书写元素的默认样式
    2，写突变样式
    3，给元素的默认样式添加transition

7，变形？
    transform
        旋转  transform:rotate(45)
        缩放
        位移
        斜切

8，旋转变形？
    





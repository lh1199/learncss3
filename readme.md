# learncss--小结
####导语:
> [index.html](index.html) 是一个以480px与960px为分界,使用 ** @media ** 查询来根据不同的页面宽度进行不同的样式设置,以达到响应式效果的页面,并大量使用了HTML5标签.只响应宽度小于480px和宽度大于960px的屏幕.

## css小技能

在本页面实现过程中有几个布局技巧是很少见但使用起来得心应手的样式属性;

1. 折叠间距的解决
    如果容器和它的子元素都设有margin-top,那么容器本身的margin-top会和第一个子元素的margin-top折叠在一起,导致第一个子元素设置的margin不管用,此时解决办法是给其父元素一个padding为0;这样就可以给元素设置需要的margin值了.
    > 效果图说明 ![header1.jpg](img/header1.jpg)
                ![header2.jpg](img/header2.jpg)
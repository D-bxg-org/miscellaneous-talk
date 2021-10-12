# src href ref url

> 参考：[https://www.jianshu.com/p/9de56962c9d1](https://www.jianshu.com/p/9de56962c9d1)

## url

```java
协议://用户名:密码@子域名.域名.顶级域名:端口号/目录/文件名.文件后缀?参数=值#标志

http://localhost:3000/index.html?name=a#h1
```

## src

直接使用该路径下的资源替换这个标签。

图片和JavaScript代码通常使用这个路径，来直接替换。

## href

> 2.href
>
> href：Hypertext Reference的缩写。意思是超文本引用。
>
> href 属性的值可以是任何有效文档的相对或绝对URL，包括片段标识符和JavaScript代码段。 \<a>标签的 href 属性用于指定超链接目标的URL。
>
> 如果用户选择了\<a>标签中的内容，那么浏览器会尝试检索并显示href 属性指定的URL所表示的文档，或者执行JavaScript表达式、方法和函数的列表。 换句话说href就是用来建立当前元素和文档之间的链接。
>
> 作者：adingmoon 链接：[https://www.jianshu.com/p/9de56962c9d1](https://www.jianshu.com/p/9de56962c9d1) 来源：简书 著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

路由的性质，建立链接，而非替换。

## ref

定义链接进来的资源和引入资源的资源的关系。也就是父引用的子的数据类型。css文件就应该用这个声明。

rel=stylesheet

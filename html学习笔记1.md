# 总结了几个常见的tag及其用法
## tag的共性：
#### 1. 以<名称>开头，以</名称>结尾
#### 2. 名称的所用字母都是小写


## 总结今天学到的常用tag
#### 1. 名称为h，即head，标题
```html
<h1>待输出标题</h1>
```
#### 一共有h1,h2,h3,h4,h5,h6六级标题

#### 2. 名称为p，即paragraph text，段落文字
```HTML
<p>待输出段落文字</p>
```

#### 3.comment你也可以把它理解为注释
```html
<!--中间部分-->
```
所有的夹在<!-- -->之间的都将被注释掉

#### 4.img链接
```html
<img src="图片链接地址" alt="图片加载失败的输出内容">
<img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
```
注：唯一一个自我闭合，不夹东西的tag

#### 5.超链接(连接到另一个网页)
```HTML
<a href="http://freecatphotoapp.com">cat photos</a>
```
效果：点击文字cat photos即会跳转到http://freecatphotoapp.com页面


## 第一阶段源代码:
```HTML
<h2>CatPhotoApp</h2>
<main>
<a href="http://freecatphotoapp.com">cat photos</a>


<img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```
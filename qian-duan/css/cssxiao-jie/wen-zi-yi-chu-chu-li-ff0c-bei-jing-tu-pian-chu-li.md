### 溢出容器

* 单行文本:将多余文本以...形式显示

```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title></title>
        <link rel="stylesheet" type="text/css" href="index2.css"/>
    </head>
    <body>
        <p>
            简介：毕生浮沉在相遇与离别的浪潮之间。但美中不足的，往往是该爱的时候太吝啬，该恨的时候又太留情。不管怎样，还望你和
             我都能爱恨分明，别隐藏爱意，也别留下
        </p>
    </body>
</html>
```

```
*{
    margin: 0;
    padding: 0;
}

p{
    width: 300px;
    height: 80px;
    line-height: 20px;
    border: 1px solid black;
    overflow: hidden;
    white-space: nowrap;
    text-overflow: ellipsis;
}
```

* 多行文本:通过计算，手动打"..."

### 图片

* background-image

```
background-image:url()
```

* background-size

```
background-size:width,height
```

* background-repeat

```
background-repeat:no-repeat;/*不重复*/
```

* background-position

```
background-positio:top left;左上方
```

```
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<link rel="stylesheet" type="text/css" href="index2.css"/>
	</head>
	<body>
		<a href="http://www.taobao.com" target="_blank">淘宝网</a>
	</body>
</html>

```

```
*{
	margin: 0;
	padding: 0;
}

a{
	display: inline-block;
	text-decoration: none;
	color: #424242;
	width: 190px;
	height: 90px;
	border: 1px solid black;
	background-image: url(//img3.mukewang.com/56d3f49e000136f106000338-240-135.jpg);
	background-size: 190px 90px;

	text-indent: 200px;
	white-space: nowrap;
	overflow: hidden;
}



```

![](/assets/14.2.10.5-01.png) ![](/assets/14.2.10.5-02.png)



* 注意p标签不能套块级元素
* a标签不能套a标签




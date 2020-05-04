# HTML5.md

## 简单测试
1. B  
2.   
none：默认。定义标准的文本  
underline：定义文本下的一条线。  
overline：定义文本上的一条线  
line-through：定义穿过文本下的一条线。  
blink：定义闪烁的文本。   

## 5.3测验
C  
B  
D  
```HTML
<!DOCTYPE html>
<html lang="zh-CN">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0"
    />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
    <style>
      a {
        color: white;
      }
      a:link {
        background-color: orange;
      }
      a:hover {
        background-color: brown;
      }
      a:active {
        background-color: yellowgreen;
      }
      a:visited {
        color: while;
      }
    </style>
  </head>

  <body>
    <a href="2.html" target="_blank">点击跳转</a>
  </body>
</html>
```
```HTML
<!DOCTYPE html>
<html lang="zh-CN">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0"
    />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
  </head>

  <body>
    <p>
     新闻1
    </p>
    <p>
      新闻2
    </p>
    <p>
     新闻3
    </p>
  </body>
</html>
```

## 5.4测验
A  
C  
C
```HTML
<!DOCTYPE html>
<html lang="zh-CN">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0"
    />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
    <style>
      .father {
        position: relative;
      }
      .child {
        position: absolute;
        top: 200px;
        left: 100px;
        color: white;
      }
    </style>
  </head>

  <body>
    <div class="father">
      <img src="这里写自己图片的地址" />
      <div class="child">定位</div>
    </div>
  </body>
</html>
```

## 作业
B  
D  
A  
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      div {
        width: 100px;
        height: 100px;
        animation: w 2s infinite alternate;
        /* infinite: 无限播放；alternate：反向播放*/
      }

      @keyframes w {
        0% {
          background-color: crimson;
          transform: translate(300px, 100px);
        }

        25% {
          background-color: cadetblue;
          transform: translate(400px, 100px);
        }
        50% {
          background-color: coral;
          transform: translate(500px, 100px);
        }
        75% {
          background-color: darkkhaki;
          transform: translate(600px, 100px);
        }
        to {
          background-color: blueviolet;
          transform: translate(700px, 100px);
        }
      }
    </style>
  </head>

  <body>
    <div></div>
  </body>
</html>
```

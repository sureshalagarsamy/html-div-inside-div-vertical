# Div inside div horizontally center

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Div inside div vertical and horizontally center</title>
</head>

<body>
<div class="parent">
  <div class="child">test</div>
  </div>
</body>

</html>
```

```css
div.parent {
    display: table-cell;
    width: 200px;
    height: 200px;
    background: #FFF;
    vertical-align: middle;
    text-align: center;
    border: 1px solid #BBB;
}

div.child {
    display: inline-block;
    width: 50px;
    height: 50px;
    background: #DDD;
    border: 1px solid #999;
}

```


### Output

![ScreenShot](https://user-images.githubusercontent.com/6780840/27215074-4095564c-528d-11e7-8128-689e6d1b9bd1.png)

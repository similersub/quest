解答例

HTML
```html
<header id="header">
    <h1>群馬高専 電算部のホームページ</h1>
</header>
```

CSS
```css
#header {
    text-align: center;
    background-color: #333;
}
#header > h1 {
    display: inline-block;
    background: linear-gradient(to right, blue, red);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
}
```

[実行例](https://similersub.github.io/quest/3-1gradient.html)
解答例

HTML
```html
<div id="container">
    <button class="menu-btn">ファイル</button>
    <button class="menu-btn">編集</button>
    <button class="menu-btn">選択</button>
</div>
```

CSS
```css
#container {
    width: 300px;
    display: flex;
    flex-direction: row;
    background-color: #00f;
}
button.menu-btn {
    width: 80px;
    margin: 10px;
}
```

[実行例](https://similersub.github.io/quest/1-2side.html)
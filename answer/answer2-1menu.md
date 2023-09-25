解答例

HTML
```html
<div id="menu"></div>
<label id="menu-button">
    <span>toggle</span>
    <input type="checkbox">
</label>
```

CSS
```css
body {
    margin: 0px;
}
#menu {
    width: 200px;
    position: fixed;
    inset: 0 0 0 auto;
    background-color: blue;
    display: none;
    &:has( + #menu-button > input:checked){
        display: block;
    }
}
#menu-button {
    display: grid;
    width: 100px;
    height: 50px;
    background-color: red;
    place-items: center;
    user-select: none;
    & > input{
        display: none;
    }
}
```

[実行例](https://similersub.github.io/quest/2-1menu.html)
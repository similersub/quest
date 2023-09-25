解答例

HTML
```html
<div id="container">
    <main>
        <section></section>
        <section></section>
        <section></section>
    </main>
    <aside></aside>
</div>
```

CSS
```css
body {
    margin: 0px;
}
#container {
    background-color: deepskyblue;
    margin: 0 0 100vh;
    display: flex;
    flex-direction: row-reverse;
    gap: 20px;
}
#container > main {
    flex: 1 0 auto;
}
#container > main > section {
    height: 75vh;
    &:nth-child(1) {
        background-color:#444;
    }
    &:nth-child(2) {
        background-color: #888;
    }
    &:nth-child(3) {
        background-color: #ccc;
    }
}
#container > aside {
    background-color: red;
    width: 200px;
    height: 300px;
    position: sticky;
    top: 0;
}
```

[実行例](https://similersub.github.io/quest/3-2sticky.html)
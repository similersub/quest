問題　以下に「メニュー」「メニューボタン」の仕様を示す。「◇」を満たすCSSのセレクタを一つ答えよ。
  - 「メニューボタン」をクリックすると「メニュー」の表示/非表示を切り替える
  - 正確には「メニューボタン」に含まれるinput要素のON/OFFに合わせて「メニュー」の表示/非表示を切り替える
  - ただし、「メニュー」と「メニューボタン」のHTML上の位置は不明である。

（この問題は「quest2-1menu」をもとに作成されています。）

HTML（メニュー）
```html
<div id="menu">
  <menu>
    <li>HOME</li>
    <li>ABOUT</li>
  </menu>
</div>
```
HTML（メニューボタン）
```html
<label id="menuButton">
  <input type="checkbox">
  <span>MENU</span>
</label>
```
CSS
```css
#menu {
  display: none;
}
◇ {
  display: block;
}
#menuButton > input{
  display: none;
}
```


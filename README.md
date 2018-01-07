## CSSのstyleを適用する方法は３つあります。  

- 外部の`CSS`ファイルをリンクする。  
```css
<link rel="stylesheet" href="css/site.css"/>

```

- ページ内部で`<style>`タグを使います。    
```css
    <style>
        h1{
            /*원하는 CSS 구현*/
            color: green;
        }

        .title{
            color: red;
        }

        p{
            color: yellow;
        }
    </style>
```

- タグの内部で`style`属性を適用します。
  
```css
<h1 style="color: blue">블루 칼라</h1>
```
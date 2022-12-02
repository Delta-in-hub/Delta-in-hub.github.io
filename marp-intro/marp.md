---
marp: true
paginate: true
_paginate: false
math: katex

style: |
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
    .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    }

---

# ![](https://tvax3.sinaimg.cn/large/005uNPwHly1h8o6xit09pj30w80a0gmi.jpg)

## <!-- fix --> 足够简单，足够好用 

> `Marp for VS code`
> https://marpit.marp.app/image-syntax?id=advanced-backgrounds
> https://github.com/marp-team/marp-core

---
# 一级标题
## 二极标题
`inline code`

```css
.columns {
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: 1rem;
}
```
$x^2 + y^2 = \frac{2}{7}$

不支持`mermaid`。  使用`---`分页。

- One
- Two
- Three

---
# <!-- fit --> Fitting header
`# <!-- fit --> Fitting header`

---

# Directives
类似`_backgroundColor`的以`_`为Local directives。
- paginate
- header
- footer
- class
- backgroundColor
- backgroundImage
- backgroundPosition (center by default)
- backgroundRepeat (no-repeat by default)
- backgroundSize (cover by default)
- color （文字颜色）

<!-- _header: _header -->
<!-- _footer: _footer -->

---

<div class="columns">
  <div>

## Column 1

`![height:300px](image.jpg)`
![height:200px](image.jpg)
`![blur:10px h:200](image.jpg)`
![blur:10px h:200](image.jpg)

  </div>

  <div>

## Column 2

```html
  <img src="example.png" style="padding: 1% 1% 1% 1%; width: 45%; " align="left" />
  <img src="image.jpg" style="padding: 1% 1% 1% 1%; width: 45%; " align="" />
  </div>
```
  <img src="example.png" style="padding: 1% 1% 1% 1%; width: 45%; " align="left" />
  <img src="image.jpg" style="padding: 1% 1% 1% 1%; width: 45%; " align="" />
  </div>
</div>

---

![bg](image.jpg)
![bg fit](example.png)

```markdown
![bg](image.jpg)
![bg fit](example.png)
```

---
![bg vertical](https://fakeimg.pl/800x600/0288d1/fff/?text=A)
![bg](https://fakeimg.pl/800x600/02669d/fff/?text=B)
![bg](https://fakeimg.pl/800x600/67b8e3/fff/?text=C)

```
![bg vertical](https://fakeimg.pl/800x600/0288d1/fff/?text=A)
![bg](https://fakeimg.pl/800x600/02669d/fff/?text=B)
![bg](https://fakeimg.pl/800x600/67b8e3/fff/?text=C)
```
---

![bg left 80%](https://picsum.photos/720?image=29)

# Split backgrounds

The space of a slide content will shrink to the right side.

`![bg left 80%](https://picsum.photos/720?image=29)`


---

![bg right](https://picsum.photos/720?image=3)
![bg](https://picsum.photos/720?image=20)

# Split + Multiple BGs

The space of a slide content will shrink to the left side.

```
![bg right](https://picsum.photos/720?image=3)
![bg](https://picsum.photos/720?image=20)
```

---

![bg left:33%](https://picsum.photos/720?image=27)

# Split backgrounds with specified size

```
![bg left:33%](https://picsum.photos/720?image=27)
```

---

![center w:600px](example.png)

图片居中`![center w:600px](example.png)`


---

# two columns

<div class="columns">
<div class="left-side">

```css
style: |
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
    .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    }

---

<div class="columns">
  <div class="left-side">

  </div>
  <div class="right-side">

  </div>
</div>
```


</div>
<div class="right-side">



![center w:500px ](image.jpg)

<div align="center">
  Text center

  1. List-1
  2. List-2
</div>

</div>
</div>

---
<!-- _backgroundColor: black -->
<!-- _color: white -->

<div align="center" style="font-size: 100px">
END
</div>
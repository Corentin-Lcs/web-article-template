<h1 align="center">Web Article Template</h1>

The "Web Article Template" GitHub project is a web article template. It includes a title, subtitle and section titles to make the content clearer and better structured. Animated section titles allow readers to quickly locate the information they're interested in and navigate through the text easily with visually engaging transitions. The design is clean and in the modern digital style.

<p align="center">
  <img src="https://github.com/Corentin-Lcs/web-article-template/blob/main/Articles.png" alt="Articles.png"/>
</p>

## Usage

A color palette is available in the `style.css` file :

```css
:root {
  --red-color: #ff3232;
  --orange-color: #ff9f1c;
  --yellow-color: #ffe600;
  --green-color: #21fe3e;
  --blue-color: #008cff;
  --pink-color: #ff00ff;
  --purple-color: #b300ff;
  --brown-color: #8b4513;
  --black-color: #000000;
  --gray-color: #808080;
  --white-color: #ffffff;
}
```

To change the color of titles or text using the palette, here's what to write :

```css
.class-title {
  ...
  color : var(--color-name-color);
  ...
}

.class-title {
  ...
  color : var(--blue-color); /* Exemple : blue color */
  ...
}
```

## Project's Structure

```
web-article-template/
├─ README.md
├─ LICENSE
├─ Articles.png
└─ src/
   ├─ index.html
   ├─ style.css
   └─ script.js
```

## Meta

Created by [@Corentin-Lcs](https://github.com/Corentin-Lcs). Feel free to contact me !

Distributed under the GNU GPLv3 license. See [LICENSE](https://github.com/Corentin-Lcs/web-article-template/blob/main/LICENSE) for more information.

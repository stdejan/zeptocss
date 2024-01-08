# ZeptoCSS - Minimalistic CSS framework
Minimalistic CSS framework without classes.

## Features
- No CSS classes - Just HTML
- Size 4KB
- Fewer than 370 lines of code
- 3 color themes

## ZeptoCSS elements:

### Typography

Paragraph:
```
<p>Paragraph</p>
```

Small text:
```
<small>Small text</small>
```

Anchor tag:
```
<a href="#">Linked text</a>
```

Highlighted text:
```
<mark>Highlighted text</mark>
```

Headings:
```
<h1>Heading 1</h1>

<h2>Heading 2</h2>

<h3>Heading 3</h3>

<h4>Heading 4</h4>

<h5>Heading 5</h5>

<h6>Heading 6</h6>
```

![Typography](https://github.com/stdejan/zeptocss/blob/main/blob/typography.png?raw=true)

### Form elements

Text input:
```
<input type="text" placeholder="ZeptoCSS" value="">
```

Textarea:
```
<textarea placeholder="ZeptoCSS"></textarea>
```

Input type number:
```
<input type="number" placeholder="24">
```

Select box:
```
<select>
    <option>Option 1</option>
    <option>Option 2</option>
    <option>Option 3</option>
</select>
```

Color picker:
```
<input type="color">
```

Date picker:
```
<input type="date">
```

Time picker:
```
<input type="time">
```

Radio buttons:
```
<div>
    <label>
        <input name="radio" type="radio" checked>
        <span>Radio 1</span>
    </label>
</div>
<div>
    <label>
        <input name="radio" type="radio">
        <span>Radio 2</span>
    </label>
</div>
```

Checkboxes:
```
<div>
    <label>
        <input name="checkbox" type="checkbox">
        <span>Checkbox 1</span>
    </label>
</div>
<div>
    <label>
        <input name="checkbox" type="checkbox">
        <span>Checkbox 2</span>
    </label>
</div>
```

Choose file:
```
<input type="file">
```

Range:
```
<input type="range" min="1" max="100" value="50">
```

Button:
```
<button>Button</button>
```

![Form elements](https://github.com/stdejan/zeptocss/blob/main/blob/form-elements.png?raw=true)

### Lists

Unordered list:
```
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

Ordered list:
```
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

![Lists](https://github.com/stdejan/zeptocss/blob/main/blob/lists.png?raw=true)

### Table

Responsive table:
```
<div style="overflow-x: auto;">
    <table>
        <thead>
            <tr>
                <th>First name</th>
                <th>Last name</th>
                <th>Age</th>
                <th>Country</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Dejan</td>
                <td>Stanković</td>
                <td>28</td>
                <td>Serbia</td>
            </tr>
        </tbody>
    </table>
</div>
```

![Table](https://github.com/stdejan/zeptocss/blob/main/blob/table.png?raw=true)

### Image

Responsive image:
```
<img src="blob/nature.jpeg" alt="image">
```

![Image](https://github.com/stdejan/zeptocss/blob/main/blob/image.png?raw=true)

### Article

Article represented as card:
```
<article>
    <img src="blob/nature.jpeg" alt="image">

    <h3>Article card</h3>

    <p>Lorem ipsum text</p>

    <footer>
        Footer text
    </footer>
</article>
```

![Article](https://github.com/stdejan/zeptocss/blob/main/blob/article.png?raw=true)

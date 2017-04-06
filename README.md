> Simple script to select text in document, just pass it dom element

### Usage

```
npm install select-text
```

Plain Javascript
```javascript
document.onclick = function(e) {
    if (e.target.className === 'click') {
        selectText('selectme');
    }
};
```

```html
<div id="selectme"><p>Some text goes here!</p><p>Moar text!</p></div>
<p class="click">Click me!</p>
```

With React

```jsx
<div
    onClick={(e) => {
        selectText()
    }}
>
    Select Me!
</div>
```

### Credits

Taken from http://stackoverflow.com/a/987376

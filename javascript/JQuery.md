# JQuery

1. Target a selector on your page

```js
var selector = $('.my-class-name'); // or '#my-id'
```

2. Use `console.log` to output the width of that element.

```js
console.log( selector.width() );
```

3. Create a function that returns something and run it.

```js
function myFunction() {
    return 'This is my function';
}}

console.log( myFunction() );
```

4. Use jQuery to get the width of the current browser window.

```js
var theWindow = $(window);
```

5. Now modify `myFunction()` to output the window width.

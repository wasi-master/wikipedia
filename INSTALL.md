### [Wikipedia](https://www.wikipedia.com)

#### Install using Stylus

If you have the [stylus](https://add0n.com/stylus.html) extension installed, you can install the theme and keep up to date by clicking the following button:

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/wasi-master/wikipedia/master/wikipedia.user.css)

#### Install manually

Copy the code from [wikipedia.user.css](https://raw.githubusercontent.com/wasi-master/wikipedia/master/wikipedia.user.css) and use your desired method of injecting css like another extension. 

You can also run the folowing javascript code in the console every time you visit the page. To open the console press
- Windows: <kbd>Ctrl+Shift+J</kbd> or <kbd>Ctrl+Shift+I</kbd> then press <kbd>Console</kbd>
- MacOS: <kbd>Option + ⌘ + J</kbd>

Then paste the following code: 
```js
$(document.head).append('<link rel="stylesheet" href="https://raw.githubusercontent.com/wasi-master/wikipedia/master/wikipedia.user.css">');
```
Note: Firefox users may need to type `allow pasting` in order to paste the code
<!-- #### Activating theme !-->
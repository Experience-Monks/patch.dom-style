## dom-style

## :warning: DEPRECATED :warning:

This module exists to fix some [kik/Azer](http://blog.npmjs.org/post/141577284765/kik-left-pad-and-npm) issues. New projects should not depend on this.

---

Inline CSS manipulation library

```js
var style = require('dom-style')

style(document.body, 'background-color', 'red')

style(document.body, {
  'font-color': 'yellow',
  'border': '5px solid black'
})

style.show(document.body.children[0])
style.hide(document.body.children[1])
```

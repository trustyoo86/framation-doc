---
description: Animation utility plugin using pure javascript or jquery
---

# framation

### get started

Install using npm or yarn

```bash
# npm
$ npm i framation --save
# yarn
$ yarn i framation
```

Added target tag in your html.

```markup
<div class="test"></div>
```

Use your javascript

```javascript
import Framation from 'framation';
// or
const Framation = require('framation');

var ani = new Framation();

ani
  .set(document.querySelector('.test'), {left: '100px', time: 2000})  // test element move left 100px during 2seconds
  .set(document.querySelector('.test'), {left: '200px', time: 2000})  // test element move left 200px during 2seconds after move left 100px
```




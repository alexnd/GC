# GC

Navigation: [BASH](#bash)
|
[GIT](#git)
|
[SSH](#ssh)
|
[PHP](#php)
|
[SQL](#sql)
|
[NODE](#nodejs)
|
[JS](#js)
|
[TS](#ts)
|
[jQuery](#jquery)
|
[VUE](#vue)
|
[MacOSX](#osx)
|
[Links](#links)

## WTF?

*Goodness Corp*? or *Garbage Collector*? Who knows...

Maybe its *Gists Collection*, no its *Gone Cuties*! LOL! ROFL! and LMAO...

I started this collection named "GC" in relationship but not only for [JS](#js).

You would feel as on a dump waste as well as happiest of happy-nanny nyan cat!

To be clear, this is not just a garbage-like log, but mix of proven solutions even with copy-paste from good sites.

Enjoy!

![HTML Colors Table](./hexcolors.png)

# [MARKDOWN](https://github.com/showdownjs/showdown/wiki/Showdown's-Markdown-syntax)

# HTML/CSS

* [CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)

* Embed css to html

```
<style>
@import '/main.css';
</style>
<!-- or -->
<link rel="stylesheet" href="/main.css">
```

* Minimal pic

```
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mP8z8BQDwAEhQGAhKmMIQAAAABJRU5ErkJggg==">

<img src="data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==">
```

```
background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mP8z8BQDwAEhQGAhKmMIQAAAABJRU5ErkJggg==);

background-image:url(data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==);
```

* Fixed-width breakpoints media queries:

```
@media (min-width: 576px) {
  .container {
    max-width: 540px;
  }
}

@media (min-width: 768px) {
  .container {
    max-width: 720px;
  }
}

@media (min-width: 992px) {
  .container {
    max-width: 960px;
  }
}

@media (min-width: 1200px) {
  .container {
    max-width: 1140px;
  }
}
```

Hex values from 100% to 0% alpha:
```
100% — FF, 99% — FC, 98% — FA, 97% — F7, 96% — F5, 95% — F2, 94% — F0, 93% — ED, 92% — EB, 91% — E8
90% — E6, 89% — E3, 88% — E0, 87% — DE, 86% — DB, 85% — D9, 84% — D6, 83% — D4, 82% — D1, 81% — CF
80% — CC, 79% — C9, 78% — C7, 77% — C4, 76% — C2, 75% — BF, 74% — BD, 73% — BA, 72% — B8, 71% — B5
70% — B3, 69% — B0, 68% — AD, 67% — AB, 66% — A8, 65% — A6, 64% — A3, 63% — A1, 62% — 9E, 61% — 9C
60% — 99, 59% — 96, 58% — 94, 57% — 91, 56% — 8F, 55% — 8C, 54% — 8A, 53% — 87, 52% — 85, 51% — 82
50% — 80, 49% — 7D, 48% — 7A, 47% — 78, 46% — 75 ,45% — 73, 44% — 70, 43% — 6E, 42% — 6B, 41% — 69
40% — 66, 39% — 63, 38% — 61, 37% — 5E, 36% — 5C, 35% — 59, 34% — 57, 33% — 54, 32% — 52, 31% — 4F
30% — 4D, 29% — 4A, 28% — 47, 27% — 45, 26% — 42, 25% — 40 ,24% — 3D, 23% — 3B, 22% — 38, 21% — 36
20% — 33, 19% — 30, 18% — 2E, 17% — 2B, 16% — 29, 15% — 26, 14% — 24, 13% — 21, 12% — 1F, 11% — 1C
10% — 1A, 9% — 17, 8% — 14, 7% — 12, 6% — 0F, 5% — 0D, 4% — 0A, 3% — 08, 2% — 05, 1% — 03, 0% — 00
```

* [What Is A CSS Reset?](https://cssdeck.com/blog/what-is-a-css-reset/)

* [Reset.css](https://github.com/richclark/HTML5resetCSS)

* [Nomalize.css](https://github.com/necolas/normalize.css)

* [Reboot.css](https://getbootstrap.com/docs/5.0/content/reboot/)

* [Destyle.css](https://github.com/nicolas-cusan/destyle.css/blob/master/Readme.md)

* [Web Design in 4 minutes](https://jgthms.com/web-design-in-4-minutes)

* [22 css ninja tricks](https://betterprogramming.pub/22-css-tricks-that-can-make-you-a-layout-ninja-452847fba639), [css box-shadow examples](https://getcssscan.com/css-box-shadow-examples)

* [The div that look different in every browser, Codepen](https://codepen.io/MartijnCuppens/pen/MXojmw)

* Download website icon via Google S2 Converter: `http://www.google.com/s2/favicons?domain=example.com`

* Fonts databases, lookup Google/Adobe by url:

```
https://fonts.google.com/specimen/FONTNAME
https://fonts.adobe.com/fonts/FONTNAME
```

# [JS](https://stackify.com/learn-javascript-tutorials/)

So, why **Javascript**?

I really not have an answer immediately...

Because, for example I can just run, in one line:

`"foo".length`

Or another one

`"foo".match(/FOo/i)`

Or even

`++"foo1".match(/FOo(\d+)/i)[1]`

Or *IIFE*, *JIT*, *events bubbling*, *functions binding*, whatever... you know?

Nevermind, if you do ;) Its kick your ASs! Just remember - GC!

Ok, well, shuffling some another stuff...

* [Js basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics), [GO](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects), [types](https://javascript.info/types), [Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions), [this](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this), [new](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new), [null](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null), [undefined](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined), [=>](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions), [Symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)

* [JS operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators)

* [for...of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of) `var A = [....]; for (var v of A) { /* v is A[i] */ }`

* [for..in](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in) `var OB = {....}; for (var K in OB) { /* K is key, OB[K] is value */ }`

* [Array.isArray](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/isArray), [Array.includes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes), [Array.from](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from), [Array.splice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice), [Array.forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach), [Array.filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter), [Array.map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map), [Array.find](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)

* [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise), [Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*), [Promises support](https://caniuse.com/promises), [ES6 Promise polyfill](https://github.com/stefanpenner/es6-promise)

* [Async loop issues](https://stackoverflow.com/questions/37576685/using-async-await-with-a-foreach-loop)

* [Object.keys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys), [Object.entries](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries)

* [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map), [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set), [ArrayBuffer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer), [Int32Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Int32Array), [BigInt64Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt64Array), [btoa](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/btoa)

* [JS Event Loop](https://developer.mozilla.org/en/docs/Web/JavaScript/EventLoop)

* [Web Api](https://developer.mozilla.org/en-US/docs/Web/API), [WebAssembly](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly)

* [Custom DOM events](https://developer.mozilla.org/en-US/docs/Web/Guide/Events/Creating_and_triggering_events), [Custom events in JavaScript: A complete guide](https://blog.logrocket.com/custom-events-in-javascript-a-complete-guide/)

* [JS debugging tips](https://raygun.com/learn/javascript-debugging-tips)

* [console.assert](https://developer.mozilla.org/en-US/docs/Web/API/Console/assert)

* [export statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export), [CommonJS modules](https://nodejs.org/api/modules.html)

* [Clean JS](https://github.com/ryanmcdermott/clean-code-javascript)

* [JS code standart by Shopify](https://github.com/Shopify/javascript)

* [JS code standart by AirBnb](https://github.com/airbnb/javascript)

* [Eloquent Javascript Book](https://eloquentjavascript.net/index.html), [WTFJS](https://github.com/denysdovhan/wtfjs)

* `"use strict"` enable [Strict Mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode) in ES5/6

* "Arraify" function arguments: `Array.prototype.slice.call(arguments)`

* Last item of array: `var last = a.slice(-1)[0]`

* Remove n-th array item: `var b = a.splice(n, 1)`

* Concatenate arrays `a` and `b`: `var c = a.concat(b)`

* Insert element at the beginning of array `var a = [.....]; [item].concat(a)` 

* Random array element: `a[Math.floor(Math.random() * a.length)]`

* Unique array elements

    `Array.from(new Set(source))` or `let b = [.....];let a = [...new Set(b)]`

* Backward-loop 

    `var a = ['a','b','c']; for ( var i=a.length; i-- > 0; ) { console.log(a[i]) }`

* Part of array from n-th item to m-th

    `var b = a.slice(n, m)` or `a.slice(0, n)` - take first n items

* You don't need *lodash* to do that, *Array.prototype* has *filter*, *map*, *reduce*...

    `arr.filter(function (v){ return v !== '' }) // return new array from arr, removing empty items`

* Check 2 arrays for equality

    - only the same values, without order conformity

    ```
    function arraysEqual(a, b) {
      if (a === b) return true
      if (a == null || b == null) return false
      if (a.length !== b.length) return false
      for (let v of b) {
        if (!a.includes(v)) return false
      }
      return true
    }
    ```

    - with order equality

    ```
    function arraysEqual(a, b) {
      if (a === b) return true
      if (a == null || b == null) return false
      if (a.length !== b.length) return false
      const c = Array.from(a)
      c.sort()
      const d = Array.from(b)
      d.sort()
      for (var i = 0; i < c.length; ++i) {
        if (c[i] !== d[i]) return false
      }
      return true
    }
    ```

* Check are 2 arrays have intersection

```
    function arraysIntersect (a, b) {
      try {
        for (let i = a.length; i--;) {
          for (let j = b.length; j--;) {
            if (a[i] === b[j]) return true
          }
        }
        return false
      } catch (e) {
        return null
      }
    }
```

* Random float number between *min* and *max*

```
    function rndA(min, max) {
      return Math.random() * (max - min) + min
    }
```

* Random integer number between *min* and *max*

```
    function rndB (min, max) {
      return Math.floor(Math.random() * (max - min + 1)) + min
    }
```

* Random point in unit circle

```
    function rndC() {
      let t = 2 * Math.PI * Math.random()
      let u = Math.random() + Math.random()
      let r = (u>1) ? 2 - u : u
      return [r * Math.cos(t), r * Math.sin(t)]
    }
```

* Capitalize string

```
    function capitalize(s) {
      return s.charAt(0).toUpperCase() + s.slice(1);
    }
```

* Normalize string, removing duplicated spaces (or any repeating 'format character') 

    `str.replace(/  +/g, ' ')` or `str.replace(/\s\s+/g, ' ')`

* Date in SQL format

    `new Date().toISOString().substr(0, 10)`

    Datetime: `new Date().toISOString().substr(0, 19).replace('T', ' ')`

* Unix timestamp for moment: `Date.now()`

* Shift existing Date object by n milliseconds

    `d.setTime(d.getTime() + 1000)) // set 1 second shift`

* void operator

    ```
    void (1+2) // undefined

    // arrow function not to return value
    void setInterval(() => { ... }, 1500)
    
    // escape context from polluting
    void function aRecursion(i) {
      if(i > 0) {
        console.log(i--)
        aRecursion(i)
      }
    }(3)
    console.log(typeof aRecursion) // undefined
    ```

* Destructuring

   ```
   [a, b] = [10, 20]

   [a, b, ...rest] = [10, 20, 30, 40, 50] // rest is [30, 40, 50]

   ({a, b} = {a: 10, b: 20}) // `a` , `b` now in context

   var o = {p: 42, q: true}
   var {p: foo, q: bar} = o // vars `foo` is 42, `q` is true in context

   let key = 'z'
   let {[key]: foo} = {z: 'bar'}  // `foo` is 'bar' in context
   
   let userFields = {
      ...(email && {email}),
      ...(name && {name}),
   }
   ```
* JSX conditional attributes

  ```
  <Link
    href="some"
    {...(foo === 'bar' && {className: styles.active})}
  >Text</Link>
  ```

* Variables as object keys

    ```
    let kProp = 'foo'
    let obj = {
      name: 'Bob',
      [kProp]: 'Bar',
    ...
    }
    obj.foo
    ```

* Advanced object key-prop loop

    ```
    var obj = {x:200, y:100, ...}
    Object.entries(obj).forEach(v => {
      // v[0] : x, y, ...
      // v[1] : 200, 100, ...
    })
    ```

* Function default arguments

    ```
    function foo(v, p = true) {
      console.log(v, p);
    }
    foo(1); // 1, true
    ```

* Default function argument value, when implementation above not supported by js engine

    ```
    function test(v) {
      var v = (typeof v === 'undefined') ? 'Foo' : v
      console.log(v)
    }
    test() // Foo
    test(1) // 1
    ```

* Object pure clone, shallow copy, new object in memory

    ```
    /* make object's shallow copy
     * src - source object
     return new object */ 
    function clone(src) {
      let out, v, k;
      if (typeof src !== 'object' || src === null) {
        return src;
      }
      out = Array.isArray(src) ? [] : {}
      for (k in src) {
        v = src[k];
        out[k] = clone(v);
      }
      return out;
    }
    ```

* Object pure clone, filtered by keys

    ```
    /* make object's shallow copy, using key filter mask (only on root level)
     * src - source object
     * keys - array of keys to be filtered, strings
     * includes - boolean flag means include or exclude operation, true by default
     return new object
     depends on clone() function */
    function cloneFk(src, keys, includes = true) {
      let out, v, k;
      if (typeof src !== 'object' || src === null) {
        return src;
      }
      out = Array.isArray(src) ? [] : {}
      for (k in src) {
        if (Array.isArray(keys) && !includes && keys.includes(k)) continue;
        if (Array.isArray(keys) && includes && !keys.includes(k)) continue;
        v = src[k];
        out[k] = clone(v);
      }
      return out;
    }
    ```

* Prototype extending

```
var world = {
  width: 2048,
  heigh: 2048,
  spawnX: 420,
  spawnY: 420
}
function Entity(o) {
  console.log('*[Entity]', o)
  var _ = o || {}
  this.x = _.x || 0
  this.y = _.y || 0
}
Entity.prototype.draw = function(t) {
  console.log('*[Entity.draw]', this.x, this.y, t)
}
function Player (o) {
  console.log('*[Player]', o)
  Entity.call(this, o)
  this.x = world.spawnX
  this.y = world.spawnY
  this.width = 42
  this.height = 42
}
Player.prototype = Object.create(Entity.prototype)
Player.prototype.constructor = Player
Player.prototype.draw = function(t) {
  console.log('*[Player.draw]', this.x, this.y, this.width, this.height, t)
}
function Sky() {
  console.log('*[Sky]', arguments)
  Entity.apply(this, arguments)
}
Sky.prototype = Object.create(Entity.prototype, {
  foo: {
    writable: true,
    configurable: true,
    value: 'Bazz'
  },
  draw: {
    writable: false,
    configurable: false,
    value: function(t) {
        console.log('*[Sky.draw]', this.x, this.y, t)
    }
  },
})
Sky.prototype.constructor = Sky
var sky = new Sky()
var player = new Player()
var target = new Entity({ x: 1000, y: 1000 })
sky.draw()
target.draw()
player.draw()
```

* Async IIFE

    ```
    // async block
    (async (data) => {
      // let b = await a(...)
      // return b
    })
    
    ({foo:'Bar'}) // input
    
    // output
    .then(v => {
      // result
    })
    .catch(e => {
      // error
    })
    ```

* Sleep for milliseconds implementation

    ```
    function sleep(ms) {
       return new Promise(resolve => setTimeout(resolve, ms))
    }
    ```

* Parse *form-urlencoded* string to *Object*

    ```
    function url_decode(s) {
        return s
            .split('&')
            .map(s => s.split('='))
            .map(pair => pair.map(decodeURIComponent))
            .reduce(function(memo, [key, value]) {
                if (!(key in memo)) { memo[key] = value }
                else {
                    if (!(memo[key] instanceof Array))
                        memo[key] = [memo[key], value]
                    else
                        memo[key].push(value)
                }
                return memo
            }, {})
    }
    ```
* generate UUID, browser

    modern browsers already have `crypto.randomUUID()`

    ```
    function uuidv4() {
        return 'xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx'.replace(
	/[xy]/g,
	function(c) {
            var r = Math.random() * 16 | 0,
            v = c == 'x' ? r : (r & 0x3 | 0x8);
            return v.toString(16);
        })
    }
    ```

* generate UUID, node

    ```
    function uuidv4() {
        return ([1e7]+-1e3+-4e3+-8e3+-1e11).replace(
	/[018]/g,
	c => (c ^ crypto.getRandomValues(new Uint8Array(1))[0] & 15 >> c / 4).toString(16)
        )
    }
    ```

* Ajax call, [fetch polyfill](https://github.com/github/fetch)

    ```
    var token = '...'
    var form = new FormData(document.getElementById('login-form'));
    fetch('/login', {
      method: 'POST',
      headers: {
        'Content-Type': 'application/x-www-form-urlencoded', // application/json
        'Authorization': 'Bearer ' + token
      },
      mode: 'cors',
      cache: 'no-cache',
      credentials: 'include',
      body: form
    })
    .then(function(res) {
      return res.json();
    })
    .then(function(data) {
      console.log('*[response]', data);
    })
    .catch(function(err) {
      console.error(err)
    });
    ```

* Js module (ES5)

    ```
    var app = (function (initData) {
    //private
      var data = {
        foo1: '1',
      }
      Object.assign(data, initData)
      var init = function(newData) { Object.assign(data, newData) }
      var test = function() { console.log(data) }
    //public
    return {
      init: init,
      test: test
    }
    })({
     foo: 'Bar',
    })
    console.log(app)
    app.init({foo2: 'Bar2'})
    app.test()
    ```

* Load JS

    ```
    let el = document.createElement('script')
    el.setAttribute('src', url)
    document.head.appendChild(el)
    ```

* Load CSS

    ```
    let el = document.createElement('link')
    el.type = 'text/css'
    el.rel = 'stylesheet'
    el.href = url
    document.getElementsByTagName('head')[0].appendChild(el)
    ```

* [Trigger DOM Event](https://developer.mozilla.org/en-US/docs/Web/Guide/Events/Creating_and_triggering_events)

```
var event = new MouseEvent('click');
var target = document.getElementById('target'); 
target.dispatchEvent(event);
```

* Wait for Element promise

    ```
    function waitForElement(selector, timeout) {
      return new Promise(function(resolve, reject) {
        var ts = Date.now();
        function queryEl() {
          var el = document.querySelector(selector);
          if (el) return resolve(el);
          if (Date.now() - ts > timeout) {
            return reject(new Error('Element ' + selector + ' not found'));
          }
          setTimeout(queryEl, 1000);
        }
        queryEl();
      });
    }
    
    // Usage example: awaiting 30 seconds for element with class="test"
    waitForElement('.test', 30000)
      .then(function(el) {
        // TEST PASSED
        console.error('Found element .test:', el.innerText);
      })
      .catch(function(err) {
        // element not found and time is out
        console.error(err.message);
      });
    ```

* Fix npm install errors like next:

```
npm ERR! code EINVALIDTAGNAME
npm ERR! Invalid tag name ">=^16.0.0" of package "react@>=^16.0.0": Tags may not have any characters that encodeURIComponent encodes.
```

  - Run `npm install --legacy-peer-deps`

# [TS](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)

* [TS Playground](https://www.typescriptlang.org/play)

# [JQuery](https://api.jquery.com)

* Entrypoint

```
$(document).ready(function() {
  //job
})
```

* Bind event handler to element with attribute `<a href="#action" id="mybutton"></a>`

```
$('#mybutton').on('click', function(e) {
  e.preventDefault()
  //job
})
```

* Trigger DOM event

```
$('selector').trigger('click')
```

* Trigger focus event and do extra stuff

```
$('selector').focus(function() {
  $(this).next('span').css('display', 'inline').fadeOut(1000)
});
```

* AJAX request

```
$.ajax({
  url: '/api/endpoint',
  type: 'POST',
  data: { foo: 'Bar' },
  cache : false,
  processData: false,
  contentType: false,
  headers: {
    'X-CSRF-Token': $('meta[name="csrf-token"]').attr('content')
    // customize request headers
  },
  error: function(xhr) {
    var errors = xhr.responseJSON.errors || {}
    //handle errors
  },
  beforeSend: function(xhr) {
    //show loader indicator
  },
  success: function(data) {
    console.log('*[XHR SUCCESS], data)
    //OK
  }
})
```

* [Extending JQuery](https://learn.jquery.com/plugins/basic-plugin-creation/)

```
// add custom function
(function( $ ) {

    $.fn.superFeature = function() {
        // super feature code
    };

}( jQuery ));
// use us
$().superFeature();
```

* [Peaks.js - audio waveform viewer](https://github.com/bbc/peaks.js)

# [PIXIJS](https://pixijs.download/dev/docs/index.html)

* [pixi-viewport](https://github.com/davidfig/pixi-viewport), [pixi-viewport docs](https://davidfig.github.io/pixi-viewport/jsdoc/)
* [@pixi/tilemap](https://github.com/pixijs/tilemap)
* [pixi-ease](https://github.com/davidfig/pixi-ease)
* [tiled-to-pixi](https://github.com/axaq/tiled-to-pixi)

# [NODE.JS](https://nodejs.org/api/index.html)

* [Install Nodejs](https://nodejs.org/en/download/current/), [node distributions](https://github.com/nodesource/distributions/blob/master/README.md)

* [The Node.js Event Loop](https://nodejs.dev/learn/the-nodejs-event-loop) [Nodejs event loop](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/#what-is-the-event-loop)

* [Don't block event loop](https://nodejs.org/en/docs/guides/dont-block-the-event-loop/)

* [Global objects in Node](https://nodejs.org/api/globals.html)

* [Nexe](https://github.com/nexe/nexe)

* Upgrade nodejs on ubuntu host to current LTS version:

```
apt-get install gcc g++ make curl build-essential
curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
```

* List global modules: `npm -g list`

* [Install](https://docs.npmjs.com/cli/v6/commands/npm-install) module globally: `npm i -g live-stream-radio`

* Vue Developer Must Have: `npm i -g @vue/cli-service-global @vue/cli npm-check-updates serve nmv pm2 nodemon`

* Install and add to package.json dependencies: `npm i -P <package>`

* Install and add to package.json devDependencies: `npm i -D <package>`

* Uninstall: `npm uninstall <package>`

* Full re-install npm-managed project: `rm -rf ./node_modules && rm ./package-lock.json && npm i --force`

* Find all available npm module versions: `npm view node-sass versions` or `npm show node-sass@* version`

* Update npm itself: `sudo npm update -g`

* List updatable: `npm outdated -g`

* Find installed foo: `npm list -g | grep foo`

* Fix broken npm: `npm cache clean --force`

* Useful npms:

`dotenv`
[dotenv-expand](https://itnext.io/master-environment-variables-on-node-js-with-dotenv-expand-f9724b310bc7)
`pm2 nodemon serve http-server eslint express body-parser socket.io knex cron redis mongodb`
[mongoose](https://mongoosejs.com)
`nodemailer multer bcrypt web3 passport`
[passport-jwt](http://www.passportjs.org/packages/passport-jwt)
[puppeteer](https://pptr.dev/#?product=Puppeteer&version=v5.4.1&show=outline)
[jimp](https://github.com/oliver-moran/jimp)
[node-ipc](https://www.npmjs.com/package/node-ipc)
[list.js](https://github.com/javve/list.js)
[node-webcam](https://github.com/chuckfairy/node-webcam)
[mediasoup](https://mediasoup.org/documentation/v3/)
[johnny-five](http://johnny-five.io/)
[handlebars](https://handlebarsjs.com/guide/), [>130 handlebars helpers](https://github.com/helpers/handlebars-helpers)

* [Tingodb](http://www.tingodb.com/) - embedded db version with storage in filesystem and API close to Mongodb, [tingodb api](https://npmdoc.github.io/node-npmdoc-tingodb/build/apidoc.html)

* [socket.io](https://socket.io/docs/v3) [socket.io-server](https://socket.io/docs/v3/server-installation/) [socket.io-client](https://socket.io/docs/v3/client-api/)

* upgrade package.json dependencies to latest versions

   ```
   npm i -g npm-check-updates
   ncu -u
   npm install
   ```

* async block in main context

    ```
    (async () => {
      await foo();
      // rest of code
    })();
    ```

* argc/argv example: `const doClean = process.argv.length > 2 && process.argv.indexOf('--clean') !== -1`

* Reading a *.py* config file into json-valid string


    Python file `config.py`:

    ```
    #!/usr/bin/env python
    config = {
    	"foo": "Bar",
	...
    }
    ```

    Nodejs code to read python file:

    ```
    var pycfg = require('fs').readFileSync('../config.py').toString()
    pycfg = pycfg.replace(/#.*\n|\r/g, '').replace('config = ', '').replace(/'/g, '"')
    var cfg = JSON.parse(pycfg)
    console.log(cfg.foo)
    ```

* Nodejs console input

    ```
    const readline = require('readline')
    const rl = readline.createInterface({
      input: process.stdin,
      output: process.stdout
    })
    rl.question('Whatsup?', (answer) => {
      console.log(`input: ${answer}`)
      rl.close()
    })
    ```

* Nodejs list network interfaces

    ```
    // long
    const hostname = os.hostname();
    const { networkInterfaces } = os;
    const nets = networkInterfaces();
    const interfaces = {}
    for (const name of Object.keys(nets)) {
      for (const net of nets[name]) {
          // Skip over non-IPv4 and internal (i.e. 127.0.0.1) addresses
          // 'IPv4' is in Node <= 17, from 18 it's a number 4 or 6
          const familyV4Value = typeof net.family === 'string' ? 'IPv4' : 4
          if (net.family === familyV4Value && !net.internal) {
              if (!interfaces[name]) {
                  interfaces[name] = [];
              }
              interfaces[name].push(net.address);
          }
      }
    }
    // { en0: [ '192.168.1.72' ] }
    console.log('*interfaces', interfaces);
    // short, but with callback
    const os = require('os');
    const dns = require('dns');
    dns.lookup(os.hostname(), function (err, addr, fam) {
      console.log('*ADDR:', addr);
    });
    ```

* [node-weak](https://www.npmjs.com/package/weak)

* `btoa()` polyfill for Nodejs, encode to Base64 (Binary to Ascii)

    `Buffer.from(asciiData).toString('base64')`

* `atob()` polyfill for Nodejs, decode from Base64 (Ascii to Binary)

    `Buffer.from(b64Encoded, 'base64').toString()`

* `fetch()` polyfill for Nodejs: `import fetch from 'isomorphic-unfetch'` (should be installed via `npm i isomorphic-unfetch`)

* Convert commonJS node app to ESmodule, not modifying type to "module" in package.json and not refactoring all existing exports

    - **do not** change type of module in package.json

    - rename entrypoint file from **JS** to **MJS** (e.g. app.js to app.mjs)

    - now you can use new export style like `import { Foo } from 'bar'` and `export { Foo }`

    - add **require()** function polyfill to save all existing require's imports:

    ```
    import { createRequire } from 'module';
    const require = createRequire(import.meta.url);
    ```
    
    - **__dirname** global polyfill:

    ```
    const url = require('node:url');
    const __filename = url.fileURLToPath(import.meta.url);
    const __dirname = path.dirname(__filename);
    ```

# [VUE](https://ru.vuejs.fsqlorg/v3/guide/index.html)

* [vue-cli](https://cli.vuejs.org/), [vue devserver-proxy](https://cli.vuejs.org/config/#devserver-proxy)

* [vue-router](https://next.router.vuejs.org/)

* [vuex](https://next.vuex.vuejs.org/), [vuex-persistedstate](https://www.npmjs.com/package/vuex-persistedstate)

* [vue-devtools](https://github.com/vuejs/vue-devtools)

* [vue native](https://vue-native.io/)

* [awesome-vue-3](https://github.com/vuesomedev/awesome-vue-3)

component.vue

```
<template>
  <foo-bar v-model="x" @click.prevent.stop="barFoo" />
  <!-- in VUE3 multiple root nodes supported -->
  <img src="@/assets/logo.png" />
  <form @submit.prevent><select v-model="ch" ref="selCh">...</select></form>
</template>
<script>
/* eslint-disable no-console,vue/no-unused-components */
import { mapState } from 'vuex'
import FooBar from 'theme/components/Foo'
export default {
  name: 'Bar',
  components: {
    FooBar
  },
  props: {
    msg: {
      type: String,
      required: false,
      default: ''
    }
  },
  data () {
    return {
      x: 0
    }
  },
  created () {},
  beforeMount () {},
  computed: {
    ...mapState({
      currentUser: state => state.user.current,
      barX () {
        return 1000 * this.x
      }
    })
  },
  methods: {
    barFoo() {}
  }
}
</script>
<style type="css">
@import '~@/assets/css/main.css';
</style>
```

[Vue3 Guide](https://v3.vuejs.org/guide/introduction.html)

[Pass elements by refs composed by v-for](https://stackoverflow.com/questions/52086128/vue-js-ref-inside-the-v-for-loop)

[Properly vuex state mutation](https://gist.github.com/DawidMyslak/2b046cca5959427e8fb5c1da45ef7748)

[Set up Vue 3 linting in VSCode](https://simohamed.tech/blog/vue3-lint/)

[Eslint Vuejs rules](https://eslint.vuejs.org/rules/)

Init VUE PWA boilerplate

```
sudo npm i -g @vue/cli @vue/cli-service-global
vue init projectname
...a bunch of options
cd projectname
npm run serve
```

Vue cli web GUI: `vue ui`

Instant vue prototyping

* Create vue component

    ```
    mkdir test
    cd test
    touch Test.vue
    ```

* Edit Test.vue (`vim Test.vue`)
    
* Optional dependencies

    Install optional dependencies via terminal: `npm init -y && npm i dependency`

    Import them in vue js code:

    `import { foo } from 'dependency'`

* Run via vue-cli instantly: `vue serve Test.vue`
    
* Open http://localhost:8080

* Define port and automatically open browser: `vue serve -o -p 5000 Test.vue`

* Optionally existing `index.html` will be reused

# [Nuxt.js](https://ru.nuxtjs.org/docs/2.x/get-started/installation)

* `npm init nuxt-app@latest NAME`

* [@nuxtjs/proxy](https://www.npmjs.com/package/@nuxtjs/proxy)

# [BASH](https://learnxinyminutes.com/docs/bash/)
# SHELL

* Create Symbolic Link: `ln -s source target`

* Pack dir to TAR + GZ: `tar -zcvf name.tgz path`

* Unpack TGZ: `tar -xzf name.tgz`

* Unpack gzipped file: `gunzip -k db.sql.gz`

* Pack dir to BZ2 without absolute path: `tar -c -j -f site1.tbz -C /var/www site1`

* Pack 1 file (.gz added automatically): `gzip path`

* Copy from your pc to host over ssh: `scp source user@host:pathTo`

* Copy from host to your pc over ssh: `scp user@host:pathFrom pathTo`

For example: `scp -P 2222 root@IP-ADDR:/root/.bash_profile ./bash_profile.txt`

* Download: `wget URL`

* Advanced download: `curl -fsSL URL -O` (or replace `-O` to `-o path`)

* Restart service in debian/ubuntu: `systemctl restart nginx`

* Stats

    `top`, `htop` - system load

    `free -m`, `vmstat -s`, `cat /proc/meminfo` - memory

    `ps -ax | grep foo` - find process by name

    `systemctl show` - services

    `df -h` (`du`) - disk space

    `ip link show` - list network interfaces 

    `ifconfig`, `iwconfig`, `arp -a`, `ping google.com` - network

    `netstat -lntp`, `netstat -Ana|grep LISTEN|grep 80` - find process bind to port

* Show listening ports: `sudo netstat -tunlp`

* Create user: `sudo useradd -m username`

* Set user password: `sudo passwd username`

* Add user to root group: `sudo usermod -a -G sudo username`

* Add user FOO to group BAR: `sudo usermod -a -G BAR FOO`

* Recursively set owner:group: `chown -R username:group /path/*`

* Recursively fix read/write permissions:

    ```
    chmod 755 $(find /path/to -type d)
    chmod 644 $(find /path/to -type f)
    ```

* Grant read/write permissions required by the web application:

    ```
    cd /var/www/website
    find . -type d -exec chmod 755 {} \;
    find . -type f -exec chmod 644 {} \;
    chown -R www-data:www-data .
    ```

* Remove user: `sudo killall -u username && sudo deluser --remove-home -f username`

* Show Debian/Ubuntu linux version: `lsb_release -a`

* List media drives: `fdisk -l`

* List usb devices: `lsusb`

* Backup disk to file, than restore it

    ```
    dd if=/dev/hda1 of=./part1.image - to backup
    dd if=./part1.image of=/dev/hda1 - to restore
    ```

* Write usb bootable from iso file:

    `dd if=./image.iso of=/dev/sdx` ( should be `sda` or `sdb` or `sdc` )

* Get random seed: `openssl rand 64 | base64` or

    `node -e "console.log(require('crypto').randomBytes(64).toString('base64'))"`

* [xargs](https://shapeshed.com/unix-xargs)

* [xclip](https://opensource.com/article/19/7/xclip)

* Install common dev stuff (like `ssh`, `vim` and `mc`) missing after clean install on debian-like os:

    ```
    sudo -s
    apt-get update
    apt-get upgrade -y
    apt install -y linux-headers-$(uname -r) net-tools wireless-tools apt-transport-https ca-certificates \
    dkms build-essential software-properties-common python gcc g++ make curl bzip2 git subversion \
    openssl libssl-dev openssh-client openssh-server screen vim mc
    ```

    - special only for ubuntu:

    `ubuntu-restricted-extras`

    - minimal MTA (sendmail)

    `nullmailer mailutils`

* Reconfigure package, running postinstall script again: `sudo dpkg-reconfigure nullmailer`

* Web developer env:

```
sudo snap install --classic certbot
sudo ln -s /snap/bin/certbot /usr/bin/certbot
apt install -y nginx curl nodejs npm php php-cli php-fpm php-json php-common php-mysql php-zip php-gd php-mbstring php-curl php-xml php-pear php-bcmath
curl -sS https://getcomposer.org/installer -o composer-setup.php
sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
```

Edit /etc/php/7.4/fpm/php.ini, set correct path's (like upload_tmp_dir) and other critical PHP settings

* configure network adapter

    -- `eth1` - interface name

    -- `sudo vi /etc/network/interfaces` :

    ```
	auto eth1
		iface eth1 inet dhcp
    ```

    (`ESC`, `i`, type..., `ESC`, `:wq`)

    -- `sudo systemctl restart networking`

* Update snap packages when it whan't:

```
sudo killall snap-store
sudo snap refresh snap-store
```

* **screen** - terminal multiplexor - keeps your terminal session on server

    - `apt install screen`

    - `screen` - start new session

    - `screen -ls` - list running sessions

    - `screen -r` - reconnect

    - `CTRL + A, D` - disconnect

    - `CTRL + A, C` - open new terminal tab

    - `CTRL + A, 0..9` - switch tab directly

    - `CTRL + A, capital K` than press `y` - to kill session

    - cool adjustment with display tabs, cpu, time - place this file on home dir `.screenrc`

```
vbell off
altscreen on
defutf8 on
termcapinfo xterm ti@:te@
hardstatus alwayslastline
hardstatus string '%{= w}%-w[ %{= W}%n %t%{-} ]%+w%=[ %{= W}%H%{-} ] [ %{= W}%l%{-} ] [ %{= W}%d.%m.%Y %c:%s%{-} ]'
```

* Network scan

```
sudo apt-get install nmap -y
nmap -sP 192.168.1.0/24
```

* `locale: Cannot set LC_*` errors

    ```
    locale: Cannot set LC_CTYPE to default locale: No such file or directory
    locale: Cannot set LC_ALL to default locale: No such file or directory
    ...
    ```

    - Client-side fix:

        - Set appropriate env vars (`EXPORT LC_ALL=$LANG`)

        - Disable sending locale information over terminal
          (on OSX unset `Set locale environment variables on startup` in `Advanced` settings tab)

    - Server-side fix:

    ```
       apt-get purge locales
       apt install locales (locales-all)
       dpkg-reconfigure locales
       locale -a
    ```

* Current date in SQL fotmat: `cdate +'%F %T'`

* Erase and watch Laravel log file

```
#!/bin/bash
DT=`date +'%F'`
truncate -s 0 ./storage/logs/laravel-$DT.log
tail -f ./storage/logs/laravel-$DT.log
```

* Import environment variables from **.env** file

    ```
    unamestr=$(uname)
    if [ "$unamestr" = 'Linux' ]; then
        export $(grep -v '^#' .env | xargs -d '\n')
    elif [[ "$unamestr" = 'FreeBSD' || "$unamestr" = 'Darwin' ]]; then
        export $(grep -v '^#' .env | xargs -0)
    fi
    ```

* [Install Certbot](https://certbot.eff.org)

* Generate new certificates on working system with nginx

    `certbot --nginx -d example.com -d www.example.com`

* Generate SSL certificates for domains via Certbot

    `certbot certonly --standalone -d example.com -d www.example.com`

* Update expired sertificates

    `certbot renew`

* [Generate SSL certificate for localhost](https://gist.github.com/cecilemuller/9492b848eb8fe46d462abeb26656c4f8)

* **CI** in 1 line of code ;)
    
    `crontab -e` - to open cron jobs file editor
    
    `*/1 * * * * cd /home/user/project && /usr/bin/git pull -q origin master >/dev/null 2>&1`
    
    The periodical job to pull from master branch
    
    **YOU SHOULD USE [WEBHOOKS](https://developer.github.com/webhooks/) / [GITLAB CI](https://about.gitlab.com/product/continuous-integration/) INSTEAD!**

* fix issues with video driver

```
add-apt-repository ppa:graphics-drivers/ppa
apt-get update
ubuntu-drivers autoinstall
```
* Upload via CURL

```
curl -i -X POST -H "Content-Type: multipart/form-data" 
-F "data=@test.mp3;userid=1234" http://mysuperserver/media/upload/
```

```
curl \
  -F "userid=1" \
  -F "filecomment=This is an image file" \
  -F "image=@/home/user1/Desktop/test.jpg" \
  http://URL
```

* CURL Ajax POST request with Authorization header:

```
#!/bin/bash

token=${@: -1}
if [ -z "${token}" ]; then
echo Enter token:
read token
fi

curl -H 'content-type: application/json' \
-H "Authorization: Bearer $token" \
-v -X POST -d '{"foo": "Bar", "baz": 0.842}' http://127.0.0.1:3000/api/fun
```

# APT

`dpkg --get-selections | grep foo` - find all packages by name `foo`

`dpkg-query --status foo` - info about package `foo`

`apt-get remove foo` - delete package `foo`

`apt-get autoremove` - delete all obsolete packages

`apt-get install -y gcc g++ make nodejs npm` - install list of packages in one line without confirmation

# [CRON](http://crontab.org/)

`crontab -l` - show current cron jobs

`crontab -e` - open crontab file with default editor 

Crontab file example:

```
# m h dom mon dow user	    command
# every minute
  * * *   *   *   www-data  wget -O - -q -t 1 http://localhost/api/cron
```

or

```
# run CMD every hour
0 * * * * CMD
```

Run every 10 minutes: `*/10 * * * *`

# SSH

* [SSH keygen](https://www.ssh.com/ssh/keygen)

`ssh-keygen -t rsa -b 4096 -C "username@example.com"`

* Prevent `git@gitlab.com: Permission denied (publickey).` connection error

    ```
    eval "$(ssh-agent -s)"
    ssh-add -l
    ssh-add -K ~/.ssh/id_rsa (or other file)
    ```

or just `ssh add`

* [How to add new ssh key](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#adding-your-ssh-key-to-the-ssh-agent)

* test access rights: `ssh -vT git@github.com`

* view ssh key fingerprint: `ssh-keygen -lf ~/.ssh/id_rsa.pub`

* [Ssh agent](https://www.ssh.com/ssh/agent)

* To easy add existing key (not .pub file) from this pc to host - `ssh-copy-id -i ~/.ssh/mykey user@host`

* To test key - `ssh -i ~/.ssh/mykey user@host`

* Cannot connect to remote host with error:

    ```
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    @    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
    IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!
    Someone could be eavesdropping on you right now (man-in-the-middle attack)!
    It is also possible that a host key has just been changed.
    ```

    edit `.ssh/known_hosts` deleting old cached host fingerprint,
    than it will be recreated at next attemp
    
    or fix with terminal cmd: `ssh-keygen -R *ip_address_or_hostname*`

* Tunneling

    `ssh -N -L localhost:6379:localhost:6379 example.com` (`-L ... -L ...` to multiply number of ports)

* [autossh](https://linux.die.net/man/1/autossh), [Permanent ssh tunnel](https://gon.gl/blog/2019/03/03/permanent-ssh-tunnel.html)

* Mount fs via sftp

    ```
    apt install sshfs
    mkdir /media/server1
    sshfs -o allow_other,follow_symlinks,IdentityFile=~/.ssh/keyfile username@hostname:/ /media/server1
    ...
    umount /media/server1
    ```
* Restricted access to host's sshd

    ```
    sudo vim /etc/ssh/sshd_config
    add line: AllowUsers goodiman good2
    sudo systemctl restart sshd
    ```
* Pass user password to ssh cmd (last resort, if you cannot `ssh -i key...`)

    ```
    sudo apt install sshpass
    sshpass -p "password" ssh user@host
    ```

# GIT

* Pretty printed commits history

`git log --pretty=oneline --abbrev-commit`

* Config

```
git config --global --get user.name
git config --global --get user.email
```

```
git config --global --list
git config --global user.name "John Doe"
git config --global user.email john@example.com
```

```
git config --get user.name
git config --get user.email
```

```
git config user.name "Your project specific name"
git config user.email "your@project-specific-email.com"
```

* Disable Fast-forward strategy

```
git config merge.ff false
git config --get merge.ff
```

* Global git settings: `~/.gitconfig`

* The local (project) configuration will be in your repository's `.git/config`

```
git init

git remote -v
git remote add

git branch

git checkout -b new_branch
git checkout other_branch
git checkout master

git branch -d localBranchName
git push origin --delete remoteBranchName

git status
git pull

git merge

git add .
git commit -m "msg"

git push -u origin master

git rm -r ObsoleteDir

git log --oneline

git checkout -- .
git reset --soft HEAD^
git reset --hard HEAD^
git reset HEAD <file>
git revert HASHCODE
git stash
git stash list
git checkout BRANCH_WHERE_YOU_STASHED
git stash apply
git stash drop

git tag -d TAGNAME
git push origin :refs/tags/TAGNAME
```

* Convert existing non-empty directory into a Git working directory and push files to a remote repository

```
cd <localdir>
git init
git add .
git commit -m 'message'
git remote add origin <url>
git push -u origin master
```

* Undo gid add: `git reset`

* [list of GIT commands](https://github.com/joshnh/Git-Commands)

* [Change remote url](https://docs.github.com/en/free-pro-team@latest/github/using-git/changing-a-remotes-url)

* [Resolving a merge conflict](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-using-the-command-line)

* [fix git permission denied](https://gist.github.com/adamjohnson/5682757) like `git@github.com: Permission denied (publickey).` when `git clone <url>`,

  you should `ssh-keygen`-ed new ssh key or use existing `~/.ssh/id_rsa.pub`,

  then add it to Github/whatever (login to that website, than find ssh keys management in your account settings)

* [GitLab](https://gitlab.com/)

# YARN

`sudo npm i -g yarn` or `brew install yarn` to install [Yarn](https://yarnpkg.com/en/)

`yarn` - bring yarn into existing npm project

`yarn install foo` - install `foo` package

`yarn remove foo` - uninstall `foo` package

`yarn dev` - run `dev` npm script

* fix `apt-get update` error `The following signatures were invalid: EXPKEYSIG 23E7166788B63E1E Yarn Packaging <yarn@dan.cx>`:

    `curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -`

# OSX

* Install [Homebrew](https://brew.sh)

  `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

* Monitor highest consuming processes

  `top -o cpu`

  `top -o rsize`

* Background services

  `launchctl list` (with ` | grep whatever`)
  
  `brew services list`

  instead of `list` use `NAME start|stop|restart` to control

* Shebang for `/usr/local/bin/*` shell scripts

    `#!/bin/sh`

    Don't forget to set executable permissions - use `chmod +x /.../bin/foo` to set it

* Screenshots

    `CMD + SHIFT + 3` - whole screen

    `CMD + SHIFT + 4` - rectangle selection dialog
    
    [Find recently made screenshots](https://osxdaily.com/2017/08/24/find-all-screenshots-mac/)

* Degree symbol ° - `OPTION(ALT) + SHIFT + 8`

* Process on port

    `sudo lsof -PiTCP -sTCP:LISTEN`

    `sudo lsof -nPi :6379`

* Mount via sftp/sshfs

    - Install [osxfuse and sshfs](https://osxfuse.github.io/) for mac:

        ```
        brew cask install osxfuse
        brew install sshfs
        ```

    - linux install: `sudo apt-get install sshfs`

    - Test ssh connection:

        `ssh -i ~/.ssh/keyfile username@hostname`

    - Mount remote share:

        ```
        mkdir /mountpath
        sshfs username@hostname:/ /mountpath
        ```

    - Unmount

        `umount /mountpath` or `diskutil umount force /mountpath`

* Remote SSH to Mac

    - Open the Apple menu in the upper left corner of the screen, and select "System Preferences...".

    - Under "Internet & Wireless", select "Sharing".

    - In the left column of services, enable "Remote Login".

    - Highlight the "Remote Login" service and enable access for the users you would like to have SSH access.

    - You can select all users, or specific users by selecting "Only these users:" and adding the appropriate users by clicking "+".

    - Take note of the command displayed underneath the words "Remote Login: On" in the upper middle part of the screen.

    - Write this command down as you will need it to log in from a different system.

    - If your firewall is enabled (which it is by default), you may need to restart the firewall to allow SSH communications to pass through port 22.

    - Open "System Prefrences", click "Security", and restart the Firewall.

    - Test that the firewall is not blocking SSH access by going to a different system and entering the ssh login command in step 6 above.

    - If you cannot login, restart the firewall or reboot.

* [How to create a bootable installer for macOS](https://support.apple.com/en-us/HT201372)

   - Install proper installation app from Appstore (Install macOS X*)

   - `sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/VOLUMENAME`

* [Change the default web browser or email app on your Mac](https://support.apple.com/en-us/HT201607)

* [TextEdit as ASCII editor](https://apple.stackexchange.com/questions/188240/built-in-gui-based-ascii-only-editor-for-os-x)

* [Supporting Associated Domains](https://developer.apple.com/documentation/xcode/supporting-associated-domains)

* [Fix](https://developer.apple.com/forums/thread/703233) for CLI error
    ```
    xcodebuild[3125:22662] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionSentinelHostApplications for extension Xcode.DebuggerFoundation.AppExtensionHosts.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
    xcodebuild[3125:22662] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionPointIdentifierToBundleIdentifier for extension Xcode.DebuggerFoundation.AppExtensionToBundleIdentifierMap.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
    ```
    when running `git` (`xcodebuild`) commands

# [Virtualbox](https://www.virtualbox.org/wiki/Downloads)

* Install Guest Additions on guest Debian/Ubuntu:

    - Required packages: `dkms linux-headers-$(uname -r) build-essential`

    - Add virtual cdrom via *Devices > Insert Guest Additions CD image*

    - Mount virtual cd `sudo mount /dev/cdrom /media/cdrom`
    
    - Run `sudo sh /media/cdrom/VBoxLinuxAdditions.run`
    
    - Reboot

* Mount shared directory inside guest Debian/Ubuntu (Guest Additions required):

    - add shared dir in Virtual machine configuration, with specifying `work` dir share name

    - inside guest os create mount point dir `mkdir ~/work`

    - mount `sudo mount -t vboxsf work ~/work`

# ESLINT

```
/* eslint-disable no-undef */
...
/* eslint-enable no-undef */
```

*.eslintrc.js*, rules:

```
// no debug
"no-console": process.env.NODE_ENV === "production" ? "warn" : "off",
"no-debugger": process.env.NODE_ENV === "production" ? "warn" : "off",
// singlequotes
"quotes": ["error", "single", { "avoidEscape": true }],
// no semicolons
"semi": ["error", "never"],
// no non-ascii chars in variables
"id-match": ["error", "^[a-zA-Z0-9_$]*$", { "properties": true, "onlyDeclarations": false }]
```

# [PYTHON](https://docs.python.org/3/)

* [Python REPL](https://repl.it/languages/python3)

* [Awesome Python](https://awesome-python.com/)

* Check os for python support: `python --version`, `python3 --version`, `pip -V`

* Linux installation: `sudo apt install python3 python3-pip`

* OSX installation: `brew install python3`

* Install [PIP](https://pypi.org/) manager:

  - `curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`
  - `python3 get-pip.py`

# [PHP](https://www.php.net/manual/en/)

0_O Wooot!?

* `apt-get install -y php7.4 php7.4-fpm php7.4-cli php7.4-mysql php7.4-curl php7.4-json`

* `declare(strict_types=1);` [Strict mode in PHP](https://www.php.net/manual/en/migration70.new-features.php)

* [php8 attributes](https://php.watch/articles/php-attributes)
* [PHP for Windows](https://windows.php.net/download)
* [Php Composer](https://getcomposer.org/download/)
* [PHP Sandbox](https://sandbox.onlinephpfunctions.com/)
* [PHP Debugbar](http://phpdebugbar.com/)
* [php-src](https://github.com/php/php-src/)
* [PHP RFC](https://wiki.php.net/rfc)
* [PSR-7](https://www.php-fig.org/psr/psr-7/)
* [PSR-12](https://www.php-fig.org/psr/psr-12/)
* [PSR-15](https://www.php-fig.org/psr/psr-15/)
* [Slim framework](https://www.slimframework.com/docs/v4/), [Slim4 Tutorial](https://github.com/odan/slim4-tutorial)
* [Session Middleware](https://odan.github.io/session/v5/)
* [Laravel Sail](https://laravel.com/docs/8.x/sail)
* [Laravel 5.x API](https://laravel.com/api/5.8/doc-index.html)
* [Laravel Blade Templates](https://laravel.com/docs/5.8/blade)
* [Laravel Debugbar](https://github.com/barryvdh/laravel-debugbar)
* [Laravel CORS](https://github.com/fruitcake/laravel-cors)
* [Setup VS Code for Efficient PHP development](https://blog.theodo.com/2019/07/vscode-php-development/)
* [PHP in Visual Studio Code](https://code.visualstudio.com/docs/languages/php)
* [21 VSCode Shortcuts To Code Faster and Funner](https://jsmanifest.com/21-vscode-shortcuts-to-code-faster-and-funner/)
* [PHP 8](https://www.php.net/index.php#id2020-11-26-3)
* [FlyImg - resize and crop images on the fly](https://flyimg.io/)
* [RxPHP](https://github.com/ReactiveX/RxPHP), [ReactPHP](https://reactphp.org/), [Typescript cms](http://typescript.org/)
* [Awesome PHP](https://github.com/ziadoz/awesome-php)
* [Design Patterns PHP](https://designpatternsphp.readthedocs.io/en/latest/README.html)
* [PHP The Right Way](https://phptherightway.com/)
* [Prevent XSS](https://www.cloudways.com/blog/prevent-laravel-xss-exploits/), [Filter user input](https://phppot.com/php/php-input-filtering/)
* [Json 2 DTO Class](https://json2dto.atymic.dev/), [DTO](https://github.com/spatie/data-transfer-object)
* [Wordpress Codex](https://codex.wordpress.org/Main_Page), [WP Code Reference](https://developer.wordpress.org/reference/), [WP Organizing Theme](https://developer.wordpress.org/themes/basics/organizing-theme-files/), [Wordpress guide](https://easywpguide.com/wordpress-manual/), [WP Themes](https://wordpress.org/themes/), [WP Plugins](https://wordpress.org/plugins/), [A Deep Introduction to WordPress Block Themes](https://css-tricks.com/a-deep-introduction-to-wordpress-block-themes)

* Filter output: `echo htmlspecialchars($string, ENT_QUOTES, 'UTF-8');`

* Filter input: `strip_tags()`, `filter_input()`, `mysqli_real_escape_string()`

* Remote IP

```
if (!empty($_SERVER['HTTP_CLIENT_IP'])) {
  $ip = $_SERVER['HTTP_CLIENT_IP'];
} elseif (!empty($_SERVER['HTTP_X_FORWARDED_FOR'])) {
  $ip = $_SERVER['HTTP_X_FORWARDED_FOR'];
} else {
  $ip = $_SERVER['REMOTE_ADDR'];
}
```

* Set correct timezone for script: `date_default_timezone_set('Europe/Kiev');`

* SQL date: `php -r 'echo  date('Y-m-d').PHP_EOL;'`

* next day SQL date: `date('Y-m-d', strtotime('+1 day'))`

* Timestamps:

```
$beginOfDay = strtotime('today', $timestamp);
$endOfDay = strtotime('tomorrow', $beginOfDay) - 1;
$endOf2Weeks = strtotime('today', strtotime('+2 weeks'));
```

* is number don't have float point

```
if (!function_exists('is_decimal')) {
    function is_decimal($n)
    {
        return is_numeric($n) && floor($n) != $n;
    }
}
```

* Parse .json file

```
$json = file_get_contents("./data.json");
if ($json) {
    try {
      $data = json_decode($json, true);
    } catch(Exception $e) {
      // handle parse error
      // $e->getMessage()
    }
} else {
  // error, no input data
}
```

* File upload

```
$uploaddir = './public/';
$tmpdir = './tmp/';
$fileKey = 'file1';
$fileSizeLimit = 2097152; // 2MB
$allowedFileTypes = ['image/png', 'image/jpeg', 'image/jpg', 'image/gif'];
$file = $_FILES[$fileKey] ?? null;
if ($file && $file['tmp_name']) {
  $fileName = basename($file['name']);
  $fileSize = $file['size'];
  $fileType = $file['type'];
  if ($fileName && $fileSize < $fileSizeLimit && in_array($fileType, $allowedFileTypes)) {
    $fileTmpPath = $tmpdir . ;
    if (is_uploaded_file($file['tmp_name'])) {
      $fp = explode('.', $fileName);
      $fileExtension = strtolower(array_pop($fp));
      $uploadFileName = join('.', $fp) . '.' . $fileExtension;
      $uploadPath = $uploaddir . $uploadFileName;
      if (move_uploaded_file($file['tmp_name'], $uploadPath)) {
        // Upload success
      }
    }
  }
}
```

* Simple Auth (2 files)

  1) cms.php (login + password required to enter)

  ```
  <?php
  session_start();
  if (empty($_SESSION['user'])) {
    header("Location: login.php");
    exit;
  }
  if (!empty($_GET['logout'])){
   unset($_SESSION['user']);
   session_destroy();
   header("Location: login.php");
  }
  ?>
  <div>
  <h1>Restricted resource<h1>
  <a href="?logout=true">Logout</a>
  </div>
  ```

  2) login.php (login form + authenticator)

  ```
  <?php
  session_start();
  $users = [
    'admin' => 'a029d0df84eb5549c641e04a9ef389e5'
  ];
  $login = $_POST['login'] ?? null;
  $password = $_POST['password'] ?? null;
  if (
    $login !== null && $login !== ''
    && $password !== null && $password !== ''
    && array_key_exists($login, $users) && $users[$login] === md5($password)
  ) {
    $_SESSION['users'] = [
      'login' => $login,
      'password' => $password
    ];
    header("Location: cms.php");
    exit;
  } 
  ?>
  <form method="post">
  <div>Username: <input type="text" name="login"></div>
  <div>Password: <input type="password" name="password"></div>
  <input type="submit" name="submit" value="Login">
  </form>
  ```

*  Guzzle HTTP request CurlFactory exception `cURL error 60: SSL certificate problem: unable to get local issuer certificate` fix

    - Download [cert file for CURL](https://curl.haxx.se/ca/cacert.pem)

    - Set php.ini variable `openssl.cafile` pointing to this file:

    ```
    [openssl]
    openssl.cafile=c:\webserver\php\extras\ssl\cacert.pem
    ```

* Strings

    ```
    php -r "echo PHP_EOL;" > eol
    ```

Have we equal output of file to `String.fromCharCode(13,10)` or just `'\n'` ?

what about this ```\x0A \x0D``` , ```x13 x10``` ?

Blame it on the typewriters - better yet, that lever or button on the right side of them. The one used to start typing on the next line. When you activate it, it causes

    the carriage to 'return' to the right so the hammers are lined up on the left side of the paper (carriage return)
    the carriage to roll up so the hammers are lined up on the next 'line' down (line feed) 

In the early 1900's teletypwriters were used to relay messages. Teletypwriters were descendants of the telegraph, and used a code similar to ASCII, called Baudot (or Murray) code. An operator could type into the teletypewriter (tty for short) and print a message on another tty far away.

In this Baudot code, two special characters were designated for a Carriage Return(0x02) and a Line Feed(0x08). Baudot code went the way of the dinosaur for reasons outside the scope of this discussion, but the CR and LF characters were adopted by ASCII with different values:

    CR = 0x0D = \015 = \r
    LF = 0x0A = \012 = \n

historically

    Macintosh: \r
    Windows  : \r\n
    Unix     : \n

different operating systems interpret a logical newline

    Unix     : \n = \012
    Macintosh: \n = \015
    Windows  : \n = \012     if handled as ASCII
    Windows  : \n = \015\012 if handled as binary

But why ```x13 x10``` ?

```0x0D``` is hexadecimal ```0D``` which is decimal 13 which is octal 15 (or ```015```).
Similarly, ```0x0A``` is hexadecimal ```0A``` which is decimal 10 which is octal 12 (or ```012```).

Following php docs about strings interpolation:

Double quoted

If the string is enclosed in double-quotes ("), PHP will interpret more escape sequences for special characters:

\n - linefeed (LF or 0x0A (10) in ASCII)
\r - carriage return (CR or 0x0D (13) in ASCII)
\t - horizontal tab (HT or 0x09 (9) in ASCII)
\v - vertical tab (VT or 0x0B (11) in ASCII)
\e - escape (ESC or 0x1B (27) in ASCII)
\f - form feed (FF or 0x0C (12) in ASCII)
\\ - backslash
\$ - dollar sign
\" - double-quote
\[0-7]{1,3} - the sequence of characters matching the regular expression is a character in octal notation
\x[0-9A-Fa-f]{1,2} the sequence of characters matching the regular expression is a character in hexadecimal notation

As in single quoted strings, escaping any other character will result in the backslash being printed too. Before PHP 5.1.1, the backslash in ```\{$var}``` had not been printed.
The most important feature of double-quoted strings is the fact that variable names will be expanded. See [string parsing](https://php.net/manual/en/language.types.string.php#language.types.string.parsing) for details.

# [NGINX](https://www.nginx.com/resources/wiki/start/index.html)

```
server {
  listen 80;
  server_name domain;
  root /var/www/domain/public;
  disable_symlinks off;
  set $path_info "";
  location / {
    index index.php index.html;
    try_files $uri $uri/ /index.php?$query_string /index.html;
    location = /favicon.ico {
      log_not_found off;
    }
    location = /robots.txt {
      log_not_found off;
    }
    location ~ /\. {
      return 404;
    }
  }
  location ~ ^/(login|logout|profile|register)/ {
    index index.html;
  }
  location ~ /\.ht {
    deny all;
  }
  location /static/ {
    alias /var/www/domain/static/;
  }
  location ~ \.php$ {
    include snippets/fastcgi-php.conf;
    fastcgi_pass unix:/run/php/php7.4-fpm.sock;
    #fastcgi_pass 127.0.0.1:9000;
    #fastcgi_pass docker-servicename:9999;
  }
  location ~ ^/(login|logout|profile|register|reset|reset-confirm) {
    rewrite /(.*) /$1 break;
    proxy_redirect off;
    proxy_set_header Host $host;
    proxy_set_header X-Real-IP $remote_addr;
    proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
    proxy_set_header X-Forwarded-Proto $scheme;
    proxy_set_header Host $http_host;
    proxy_pass http://api:${API_PORT};
  }
  location /api {
    rewrite /(.*) /$1 break;
    proxy_redirect off;
    proxy_http_version 1.1;
    proxy_set_header Upgrade $http_upgrade;
    proxy_set_header Connection "upgrade";
    proxy_set_header Host $host;
    proxy_set_header X-Real-IP $remote_addr;
    proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
    proxy_set_header X-Forwarded-Proto $scheme;
    proxy_set_header Host $http_host;
    proxy_pass http://api:3001;
    proxy_buffering off;
  }
}
```

# DB

* [Dbdiagram.io](https://dbdiagram.io/home)
* [SqlDBM](https://sqldbm.com/Home/)
* [Dbdesigner.net](https://www.dbdesigner.net/)
* [Visual Paradigm](https://www.visual-paradigm.com/features/database-design-with-erd-tools/)
* [Erwin Data Modeler](https://erwin.com/products/erwin-data-modeler/)

# SQL

* Install: `sudo apt-get install -y mysql-server`
* Init root user: `sudo mysql_secure_installation`
* Set root(user) credentials:
- `sudo mysql`
- `ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'your_new_password';`
- `FLUSH PRIVILEGES;`

* [Install MySQL 5.7 on Ubuntu](https://www.how2shout.com/linux/add-repository-to-install-mysql-5-7-on-ubuntu-20-04-lts-linux/)
* [Mysql for Windows](https://dev.mysql.com/downloads/installer/)
* [MySQL Reference Manual](https://dev.mysql.com/doc/)
* [MySQL Workbench (GUI Client)](https://dev.mysql.com/downloads/workbench/)

`select from_unixtime(2147483647)`

  =>

`2038-01-19 05:14:07` - 32-bit time_t limit (2038-year timestamp overflow)

* Date/time conversion functions:

    `SELECT FROM_UNIXTIME(UNIX_TIMESTAMP(STR_TO_DATE('Oct 19 2018 10:00PM', '%M %d %Y %h:%i%p')),'%m-%d-%Y %h:%i:%p');`
    =>
    `10-19-2018 10:00:PM`

* Select with grouping for 'daily count'

```
select
 year(created_at) date_year,
 month(created_at) date_month,
 day(created_at) date_day,
 count(*) as users_count
from users
where
 # todo: set variable date range here
 year(created_at) = 2020 and month(created_at) = 12
group by
 year(created_at), month(created_at), day(created_at)
```

* Add user with credentials (myuser mypassword) and set all privilegies to mydb

```
CREATE USER 'myuser'@'%' IDENTIFIED BY 'mypassword';
GRANT ALL PRIVILEGES ON mydb.* TO 'myuser'@'%';
```
* Add privilegies for user on db

```
GRANT ALL PRIVILEGES ON *.* TO 'myuser'@'%';
FLUSH PRIVILEGES;
```

* Rename database olddb newdb

```
CREATE DATABASE newdb DEFAULT CHARSET utf8;

RENAME TABLE olddb.table1 TO newdb.table1;
RENAME TABLE olddb.table2 TO newdb.table2;
...

DROP DATABASE olddb;
```

* Execute dynamic statement (truncate a table only if it exists)

```
SET @tableName := 'your_table_name';
SET @schemaName := 'your_schema_name';
IF EXISTS (
    SELECT 1
    FROM information_schema.tables
    WHERE table_schema = @schemaName
    AND table_name = @tableName
) THEN
    SET @truncateStmt := CONCAT('TRUNCATE TABLE ', @schemaName, '.', @tableName);
    PREPARE truncateStmt FROM @truncateStmt;
    EXECUTE truncateStmt;
    DEALLOCATE PREPARE truncateStmt;
END IF;
```

* [reset MySQL root password (ubuntu)](https://linuxconfig.org/how-to-reset-root-mysql-password-on-ubuntu-18-04-bionic-beaver-linux)

* Install vim inside mysql docker container: `microdnf install -y vim` (then you can `vim /etc/my.cnf`)

* Increase system var value that affects default limit 1024 of GROUP_CONCAT()

  - Show system var: `select @@GLOBAL.group_concat_max_len;`

  - In mysqld config (/etc/my.cnf):

    ```
    [mysqld]
    group_concat_max_len = 10000
    ```

# Mongo DB

* [Mongo for Windows](https://www.mongodb.com/try/download/community)

* [Mongodb Indexes](https://docs.mongodb.com/manual/indexes/)

* Nodejs connection to mongo (Mongoose installed via `npm i mongoose`):

```mongoose.connect(MONGO_URI, options, (err) => { ... })```

Where:

  - `const MONGO_URI = mongodb+srv://<username>:<password>@<cluster_name>.<host>/<database>`

  - `const options = {useNewUrlParser: true, useUnifiedTopology: true}`
    
  - `(err) => { ... }` callback, if no `err` object in first argument - connection success

## Mongo CLI - authorize as db admin

```
mongo
use admin
db.auth('admin', passwordPrompt())
```

## Mongo CLI - create normal user with credentials and full access to DB_NAME

  - Authorize as admin

  - ```
    use DB_NAME
    db.createUser({user:'USERNAME', pwd:'PASW', roles:[{role:'readWrite', db:'DB_NAME'}]})
    ```

## Mongodb on OSX

Start/stop server: `brew services start|stop mongodb-community`

### Add root user

  - Edit config: `vim /usr/local/etc/mongod.conf`

  - Add section that turns off authorization

    ```
    security:
      authorization: disabled
    ```

  - Restart service `brew services restart mongodb-community`

  - Login to cli and add paticular user

    ```
    mongo
    use admin
    db.createUser({user:"admin",pwd:"password",roles:[{role:"root",db:"admin"}]});
    exit
    ```

   - Comment out with `#` or delete `authorization: disabled` from mongod.conf
   
   - Restart service `brew services restart mongodb-community`

# [Redis](https://redis.io/commands)

`redis-cli`

* [Redis for Windows](https://github.com/microsoftarchive/redis/releases)

* [npm redis](https://github.com/NodeRedis/node-redis)

# VI(M)

* Press **ESC** to switch mode

    **dd** - delete line

    **:w** - save, **:q** - quit

    **:wq** - write and quit

    **:q!** - quit without saving

* Cut and paste

    Position the cursor where you want to begin cutting.

    Press **v** to select characters (or uppercase **V** to select whole lines).

    Move the cursor to the end of what you want to cut.

    Press **d** to cut (or **y** to copy).

    Move to where you would like to paste.

    Press **P** to paste before the cursor, or **p** to paste after.

    Copy and paste is performed with the same steps except for step 4 where you would press **y** instead of **d**:

    **d** = delete = cut

    **y** = yank = copy

Deleted or copied text is placed in the unnamed register. If wanted, a register can be specified so the text is also copied to the named register. A register is a location in Vim's memory identified with a single letter. A double quote character is used to specify that the next letter typed is the name of a register.

For example, you could select the text ```hello``` then type ```"ay``` to copy "hello" to the ```a``` register. Then you could select the text ```world``` and type ```"by``` to copy "world" to the ```b``` register. After moving the cursor to another location, the text could be pasted: type ```"ap``` to paste "hello" or ```"bp``` to paste "world". These commands paste the text after the cursor. Alternatively, type ```"aP``` or ```"bP``` to paste before the cursor.

You remember? **"**, than **register**, than operation (**yY dD pP**)

And yes... Please don’t cut the purple trees!

Change the lineendings in the view:

```
:e ++ff=dos
:e ++ff=mac
:e ++ff=unix
```

This can also be used as saving operation (:w alone will not save using the lineendings you see on screen):

```
:w ++ff=dos
:w ++ff=mac
:w ++ff=unix
```

And you can use it from the command-line:

```
for file in $(ls *cpp)
do 
  vi +':w ++ff=unix' +':q' ${file}
done
```

# [DOCKER](https://www.docker.com/get-started)

* [Docker Installation](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
* [Docker Toolbox](https://github.com/docker/toolbox/releases)
* [Docker Compose](https://docs.docker.com/compose/install/)
* [Best practices for writing Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
* [Docker in WSL2](https://code.visualstudio.com/blogs/2020/03/02/docker-in-wsl2)
* Fix docker-compose error `permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock:`
- Following [linux docker post-install steps](https://docs.docker.com/engine/install/linux-postinstall/):

    ```
    sudo groupadd docker
    sudo usermod -a -G docker $USER
    sudo newgrp docker
    ```
* watch logs: `docker logs -f --tail 50 container-name`
* clean logs: `truncate -s 0 $(docker inspect --format='{{.LogPath}}' container_name_or_id)`

/var/lib/docker/containers/<CONTAINER>/<CONTAINER>-json.log

# WINDOWS

* [Sysinternals Suite](https://docs.microsoft.com/en-us/sysinternals/)
* [Notepad++](https://notepad-plus-plus.org/downloads/)
* [Total Commander](https://www.ghisler.com/download.htm)
* [git-scm](https://git-scm.com/download/win), [Putty](https://www.putty.org/)
* [sshfs-win](https://github.com/billziss-gh/sshfs-win), [winfsp](https://github.com/billziss-gh/winfsp), [Mapping network driv over ssh](http://makerlab.cs.hku.hk/index.php/en/mapping-network-drive-over-ssh-in-windows)
* [autologon](https://docs.microsoft.com/ru-ru/sysinternals/downloads/autologon)
* [GIMP](https://www.gimp.org/downloads/), [Inkscape](https://inkscape.org/release/inkscape-1.1/windows/64-bit/exe/dl/)

# [ANDROID](https://developer.android.com/studio)

* [How to Install ADB on Windows, macOS, and Linux](https://www.xda-developers.com/install-adb-windows-macos-linux/)

# MISC

* Get first line of string

    js: ```s.split('\n')[0]```

    php: ```strtok($s, "\n")```

    py: ```s.split('\n', 1)[0]``` or another py: ```s.splitlines()[0]```

* cyrillic characters

`ы Ы э Э ё Ё ъ Ъ і І ї Ї є Є ґ Ґ №`

* [emoji characters list](https://unicode.org/emoji/charts/emoji-list.html) [emojipedia](https://emojipedia.org/) [emoji symbols (emojinarium)](https://emojinarium.com/symbols/)

* ssl

- [mkcert](https://github.com/FiloSottile/mkcert)

* Capture webcam

- Set permission for video device: `usermod -a -G video USERNAME`

- Install **v41-utils**: `sudo apt-get install -y v4l-utils`

- Check available devices: `sudo v4l2-ctl --list-devices`

- Get info about device: `sudo v4l2-ctl --device=/dev/video0 --all`

- Install **ffmpeg**: `sudo apt-get install -y ffmpeg`

- Run capture: `ffmpeg -f oss -f video4linux2 -s 640x480 -t 24 -i /dev/video0 ./www/video0.mpg`

# DECENTRALIZATION

* bitcoin

```
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt update
sudo apt install bitcoin-qt bitcoind
bitcoin-qt
```

* [Coins Rates](https://coincap.io/)
* [Coins calc (ETH - USD)](https://coinmarketcap.com/ru/converter/eth/usd/)
* [Wallet](https://coinbase.com)
* [Miners pool](https://2miners.com/), [CryptoCalc](https://2cryptocalc.com/), [whattomine](https://whattomine.com/), [crypt0.zone](https://crypt0.zone/calculator)
* [Metamask](https://metamask.io/)
* [Ethereum](https://eth.wiki/)
* [Ethereum Utils](https://github.com/ethereumjs/ethereumjs-util/)
* [Ethereum Web3](https://github.com/ethereumjs/web3/)
* [Metamask minimal dapp](https://github.com/MetaMask/test-dapp)
* [Metamask state for 2020](https://medium.com/metamask/breaking-changes-to-the-metamask-inpage-provider-b4dde069dd0a)
* [Dapp tutorial](https://www.dappuniversity.com/articles/how-to-build-a-blockchain-app)

# LINKS

* [GIT](https://git-scm.com/downloads)
* [VSCode](https://code.visualstudio.com/docs/setup/setup-overview), [SFTP Sync](https://marketplace.visualstudio.com/items?itemName=liximomo.sftp), [npm-scripts](https://marketplace.visualstudio.com/items?itemName=traBpUkciP.vscode-npm-scripts), [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur), [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode), [Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* [Sublime text editor](https://www.sublimetext.com/3), [Vue highlight](https://github.com/vuejs/vue-syntax-highlight), [Linux setup](https://www.sublimetext.com/docs/3/linux_repositories.html)
* [WebStorm EAP](https://www.jetbrains.com/ru-ru/webstorm/nextversion/), [PHPStorm EAP](https://www.jetbrains.com/phpstorm/nextversion/), [Jetbrains Toolbox](https://www.jetbrains.com/ru-ru/toolbox-app/)
* [Vue-cli](https://github.com/vuejs/vue-cli), [Vue-devtools](https://github.com/vuejs/vue-devtools)
* [ES2015 hints](https://devhints.io/es6)
* [Can i use](https://caniuse.com/)
* [Can i email](https://www.caniemail.com/)
* [MDN](https://developer.mozilla.org/en-US/docs/Web)
* [W3C ORG](https://www.w3.org/)
* [W3C API](https://www.w3.org/api/)
* [The Internet Engineering Task Force (IETF)](https://www.ietf.org/links/)
* [App manifest](https://app-manifest.firebaseapp.com/)
* [HTML formatter](https://www.freeformatter.com/html-formatter.html)
* [CSS Code Beautifier](http://www.codebeautifier.com/)
* [CSS Animations Playgroud](https://animista.net/)
* [HTML Color Codes](https://htmlcolorcodes.com/)
* [RGBA Converter](https://tdekoning.github.io/rgba-converter/), [RGBtoHEX](https://www.rgbtohex.net/), [rgbatohex](https://simplecss.eu/rgbatohex.html)
* [JSON formatter](https://jsonformatter.curiousconcept.com/)
* [Base64 decode](https://www.base64decode.org/), [Base64 encode](https://www.base64encode.org/)
* [MsgPack decoder/encoder](https://kawanet.github.io/msgpack-lite/), [MsgPack bindings](https://msgpack.org/)
* [Google images search](https://www.google.com/imghp)
* [GIF converter](https://ezgif.com/)
* [MakeAppIcon](https://makeappicon.com/)
* [Favicon.io](https://favicon.io/), [Real Favicon Generator](https://realfavicongenerator.net/)
* [Fonts icons generator](http://fontello.com/)
* [Vector editor](https://vectr.com/)
* [Online Img Vectorizer](https://www.vectorizer.io)
* [Boxy](https://boxy-svg.com/app)
* [SVGBox](https://svgbox.net/)
* [SVGOMG](https://jakearchibald.github.io/svgomg/), [SVGO](https://github.com/svg/svgo)
* [SVG2PNG](https://svgtopng.com/)
* [SVG Generators](https://www.smashingmagazine.com/2021/03/svg-generators/)
* [Blobmaker](https://www.blobmaker.app/)
* [FreeConvert](https://www.freeconvert.com/), [CloudConvert](https://cloudconvert.com/)
* [griddy](https://griddy.io/), [layoutit](https://grid.layoutit.com/), [css-grid-layout](https://css-grid-layout-generator.pw/), [CSS grid generator](https://cssgrid-generator.netlify.com/), [cssgr.id](https://cssgr.id), [cssgridgenerator](https://github.com/sdras/cssgridgenerator)
* [Gradient Border Generator](https://codepen.io/amit_sheen/pen/LYNKerG), [CSS Generators](https://html-css-js.com/css/generator/border-outline/), [CSS Gradient](https://cssgradient.io/)
* [1linelayouts](http://1linelayouts.glitch.me/)
* [Flexbox Help](https://flexbox.help/)
* [CSS Grid Guide](https://www.telerik.com/blogs/guide-css-grid)
* [Responsive Image Breakpoints Generator](https://www.responsivebreakpoints.com/)
* [Img to Base64](https://stephanwagner.me/online-image-to-base64-data-uri-converter)
* [Excalidraw](https://excalidraw.com/)
* [PDF converter](https://online2pdf.com)
* [JPEXS Free Flash Decompiler](https://github.com/jindrapetrik/jpexs-decompiler), [Apache Flex](https://flex.apache.org/)
* [EditorConfig](https://editorconfig.org/)
* [Hat.sh file encryptor](https://hat.sh/)
* [JWTDecoder](http://calebb.net/), [JWT.io](https://jwt.io/)
* [AST explorer](https://astexplorer.net/)
* [GSAP](https://github.com/greensock/GSAP)
* [Online Sprite Sheet Atlas Editor](https://www.leshylabs.com/apps/sstool/), [Online Sprite Sheet Packer](https://www.codeandweb.com/free-sprite-sheet-packer), [Glue tool](https://glue.readthedocs.io/en/latest/), [Spritesheet.js](https://github.com/krzysztof-o/spritesheet.js/)
* [PWA Asset generator](https://github.com/onderceylan/pwa-asset-generator)
* [Webpack module federation](https://webpack.js.org/concepts/module-federation/)
* [Upptime - uptime monitor and status page](https://github.com/upptime/upptime)
* [Frontend Checklist](https://frontendchecklist.io/)
* [SSL For Free](https://www.sslforfree.com/)
* [swagger.json editor](https://editor.swagger.io/)
* [Insomnia REST client](https://insomnia.rest/)
* [Postman - API test client](https://www.postman.com/)
* [Robo 3T MongoDB Client](https://robomongo.org/)
* [Altair GraphQL Client](https://altair.sirmuel.design/), [Chrome GraphQL Network Inspector](https://chrome.google.com/webstore/detail/graphql-network-inspector/ndlbedplllcgconngcnfmkadhokfaaln)
* [SQLite Browser](https://sqlitebrowser.org/dl/)
* [Pusher - message service](https://pusher.com/)
* [Glitch.me - online dev toolbox](https://glitch.com/)
* [Piskel - pixelart/sprite editor](https://www.piskelapp.com/)
* [SVG shape generator](https://www.softr.io/tools/svg-shape-generator)
* [SVG Crop](https://svgcrop.com/)
* [Animate.css](https://animate.style/)
* [Figma - collaborative design tool](https://www.figma.com/)
* [Mobile Friendly test](https://search.google.com/test/mobile-friendly)
* [FontSource](https://github.com/fontsource/fontsource)
* [Webfont Generator](https://www.fontsquirrel.com/tools/webfont-generator)
* [Fonts.Google](https://fonts.google.com)
* [Google webfonts helper](https://gwfh.mranftl.com/fonts)
* [FontSpace](https://www.fontspace.com)
* [1001 Fonts](https://www.1001fonts.com)
* [FontSquirrel](https://www.fontsquirrel.com)
* [Microbunle](https://github.com/developit/microbundle)
* [Storybook](https://storybook.js.org/)
* [Atomicdesign](https://atomizedesign.com/)
* [Emmet plugin](https://emmet.io/)
* [JSFiddle](https://jsfiddle.net/)
* [Code sandbox](https://codesandbox.io/)
* [JS Bin](https://jsbin.com/)
* [GitHub Gist](https://gist.github.com/)
* [CodePen](http://codepen.io/)
* [Snipplr](http://snipplr.com/)
* [Codeply](http://www.codeply.com/)
* [Codeshare](https://codeshare.io/)
* [Codepad](https://codepad.co/)
* [Dabblet](http://dabblet.com/)
* [Liveweave](http://liveweave.com/)
* [CSSDeck](http://cssdeck.com/)
* [CodeProject](http://www.codeproject.com/)
* [CollabEdit](http://collabedit.com/)
* [Pasted.co](http://pasted.co/)
* [Etherpad](http://etherpad.org/)
* [JSPerf](https://jsperf.com/)
* [ESBench](https://esbench.com/)
* [WebDev measure](https://web.dev/measure/)
* [BrowserStack](https://www.browserstack.com/)
* [AnimXYZ](https://animxyz.com/)
* [Texture packer](https://www.codeandweb.com/texturepacker)
* [WebP](https://developers.google.com/speed/webp)
* [Ruffle](https://ruffle.rs/)
* [AMP](https://amp.dev/), [AMP validator](https://validator.ampproject.org/)
* [Tiled map editor](https://www.mapeditor.org/)
* [CreateApp](https://createapp.dev/)
* [ScaffoldHub](https://scaffoldhub.io/)
* [Next.js](https://nextjs.org/)
* [Nest.js](https://nestjs.com/)
* [Nuxt.js](https://nuxtjs.org/)
* [React.js](https://reactjs.org/docs/getting-started.html), [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
* [React Online Playground](https://playcode.io/react), [Playcode react sample](https://playcode.io/1004160)
* [ReactNative](https://reactnative.dev/docs/environment-setup)
* [Tailwind.css](https://tailwindcss.com/), [Tailwind UI](https://tailwindui.com/), [WickedBlocks](https://wickedblocks.dev/), [Cleopatra - Tailwind Admin Dashboard](https://github.com/moesaid/cleopatra)
* [Adaptivejs](http://adaptivejs.mobify.com/v2.0/docs/what-is-adaptivejs/)
* [Blueprint](https://blueprintjs.com/docs/)
* [Semantic-UI](https://react.semantic-ui.com/)
* [Material-UI](https://material-ui.com/)
* [MDBootstrap](https://mdbootstrap.github.io/bootstrap-material-design/docs)
* [Ant Design](https://ant.design/)
* [MUI](https://mui.com/), [MUI Core](https://github.com/mui/material-ui/), [MUI X](https://github.com/mui/mui-x), [MUI Templates](https://mui.com/material-ui/getting-started/templates/)
* [React Bootstrap](https://react-bootstrap.github.io/)
* [React Admin](https://marmelab.com/react-admin/)
* [Shards React](https://designrevision.com/downloads/shards-react/)
* [Material Kit React](https://www.creative-tim.com/product/material-kit-react)
* [Argon](https://www.creative-tim.com/product/argon-design-system-react/)
* [React Virtualized](https://bvaughn.github.io/react-virtualized/#/components/List)
* [Onsen UI](https://onsen.io/react/)
* [React Toolbox](http://react-toolbox.io/#/)
* [React Decktop](https://reactdesktop.js.org/)
* [Evergreen](https://evergreen.segment.com/)
* [Reactstrap](https://reactstrap.github.io/)
* [Rebass](https://rebassjs.org/)
* [Grommet](https://v2.grommet.io/)
* [React Suite](https://rsuitejs.com/)
* [Elemental UI](http://elemental-ui.com/)
* [Belle](https://nikgraf.github.io/belle/)
* [React-md](https://react-md.dev/v1/)
* [Prime React](https://www.primefaces.org/primereact/)
* [Kendo React](https://www.telerik.com/kendo-react-ui/)
* [Awesome React](https://github.com/enaqx/awesome-react)
* [Awesome ReactNative](https://github.com/jondot/awesome-react-native)
* [Awesome Vue](https://github.com/vuejs/awesome-vue)
* [Awesome Vue scaffold](https://awesome-vue.js.org/components-and-libraries/scaffold.html)
* [Awesome Nodejs](https://github.com/sindresorhus/awesome-nodejs)
* [Awesome Opensource](https://awesomeopensource.com/projects/)
* [Flutter](https://docs.flutter.dev/), [Dart](https://dart.dev/guides/language/effective-dart/design), [Dart Pub (packages)](https://pub.dev/packages), [Dart Pad](https://dartpad.dev/?), [Awesome Flutter](https://github.com/Solido/awesome-flutter), [Dart cheat sheet](https://simplecheatsheet.com/tag/dart-cheat-sheet)
* [Three.js](https://threejs.org/)
* [Playcanvas](https://playcanvas.com/), [playcanvas github](https://github.com/playcanvas/engine)
* [Headless CMS list by Jamstack.org](https://jamstack.org/headless-cms/)
* [Angular.js](https://github.com/angular/angular.js), [angularjs api](https://code.angularjs.org/1.2.9/docs/api)
* [Angular](https://angular.io/), [Angular api](https://angular.io/api)
* [JSON Placeholder](http://jsonplaceholder.typicode.com/), [https://httpbin.org/](HttpBin), [api.quotable.io](https://api.quotable.io/random)
* [public-apis](https://github.com/public-apis/public-apis), [free-apis](https://apilist.fun/collection/free-apis), [mockapi](https://mockapi.io/), [fakestoreapi](https://fakestoreapi.com/docs), [dnd5eapi](https://www.dnd5eapi.co/), [yesno.wtf](https://yesno.wtf/api), [pokeapi](https://pokeapi.co/)
* [Natural Earth Data](https://github.com/nvkelso/natural-earth-vector)
* [Rest Countries](https://restcountries.eu/)
* [TimeZoneDB - Free Time Zone Database & API](https://timezonedb.com/)
* [Lorem Ipsum IO](https://loremipsum.io/)
* [Pfolios - portfolio insiration](https://pfolios.net/)
* [Undraw Illustrations](https://undraw.co/), [SVGRepo Vectors and Icons](https://www.svgrepo.com/)
* [Canvas Oldshool Demo Effect Framework](http://codef.santo.fr/)
* [Hammer.js](https://hammerjs.github.io/)
* [Game Engines](https://github.com/bebraw/jswiki/wiki/Game-Engines), [Intro HTML5 Gamedev](https://developer.mozilla.org/ru/docs/Games), [Getting Started HTML5 Gamedev](https://hacks.mozilla.org/2013/09/getting-started-with-html5-game-development/)
* [Build your own X](https://github.com/danistefanovic/build-your-own-x/blob/master/README.md)
* [Floating Point Math](https://0.30000000000000004.com/)
* [Big O cheatsheet](https://adrianmejia.com/most-popular-algorithms-time-complexity-every-programmer-should-know-free-online-tutorial-course)
* [Design Patterns](https://refactoring.guru/design-patterns), [3 Design Patterns You should know](https://www.freecodecamp.org/news/the-basic-design-patterns-all-developers-need-to-know/) [DDD](https://www.geeksforgeeks.org/domain-driven-design-ddd/), [Catalog of PEAA](https://martinfowler.com/eaaCatalog/), [GoF](https://springframework.guru/gang-of-four-design-patterns/), [BFF](https://samnewman.io/patterns/architectural/bff/)
* [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
* [Microservices](https://microservices.io/patterns/index.html)
* [OWASP Top 10](https://owasp.org/www-project-top-ten/)
* [SonarQube](https://docs.sonarqube.org/latest/)
* [ImageKit.io image CDN](https://imagekit.io/)
* [ASCII Table](https://www.asciitable.com)
* [100% JavaScript Pure Data runtime using Web Audio API](https://github.com/sebpiq/WebPd/)
* [Codemirror - js editor](https://codemirror.net/), [vpic.nhtsa.gov/api](https://vpic.nhtsa.dot.gov/api/), [SpaceX-API](https://github.com/r-spacex/SpaceX-API/blob/master/docs/README.md)
* [Count Lines of Code](https://github.com/AlDanial/cloc)
* [Nomie tracker](https://nomie.app/)
* [Blockstack apps](https://browser.blockstack.org/)
* [BigchainDb](https://github.com/bigchaindb)
* [Ganache](http://truffleframework.com/ganache)
* [WebRTC streamer](https://snapcraft.io/webrtc-streamer)
* [Diagrams.net](https://app.diagrams.net/), [Xmind Mindmap editor](https://xmind.works/), [https://xmind.app](https://xmind.app/), [Google Drawings](https://docs.google.com/drawings), [Dbdiagram.io](https://dbdiagram.io/home)
* [Notion](https://www.notion.so/)
* [RoamResearch](https://roamresearch.com/)
* [Syncthing - your own private cloud for files syncronization](https://syncthing.net/)
* [Foresty.io - Git-backed CMS](https://forestry.io/)
* [Jekyll - static site generator](https://jekyllrb.com/)
* [MailHog](https://github.com/mailhog/MailHog), [How to Use MailHog to Test Emails Locally](https://kinsta.com/blog/mailhog/)
* [Mailtrap - Safe Email Testing](https://mailtrap.io/)
* [Temp Mail](https://temp-mail.org/en/)
* [Free SMS Online](https://receive-smss.com/)
* [2captcha](https://2captcha.com/)
* [Privacypass](https://privacypass.github.io/)
* [GAOptout](https://tools.google.com/dlpage/gaoptout)
* [OpenAI API](https://beta.openai.com/docs/api-reference), [OpenAI Playground](https://beta.openai.com/playground)
* [Google Colaboratory](https://colab.research.google.com/), [Jupyter Notebook (IPython)](https://ipython.org/notebook.html)
* [Cryptocompare - exchange rates](https://cryptocompare.com), [Fixer - foreign exchange rates and currency conversion](https://fixer.io)
* [Google Analytics](http://analytics.google.com/)
* [Google Drive](https://drive.google.com/)
* [Google Docs](https://docs.google.com/)
* [Youtube downloader](https://ymp4.download/en4/), [Youtube dl CLI](https://github.com/ytdl-org/youtube-dl)
* [Everhour - time manager/tracker](https://everhour.com/)
* [Libre Office](https://www.libreoffice.org/download/download)
* [Free Office](https://www.freeoffice.com/en/)
* [Brave browser (chrome engine)](https://brave.com/download/), [Firefox developer edition](https://www.mozilla.org/uk/firefox/developer/), [Opera](https://www.opera.com/en/download)
* [Chrome extensions development](https://developer.chrome.com/docs/extensions/), [Chrome extensions API reference](https://developer.chrome.com/docs/extensions/reference/)
* [DOSBox](https://www.dosbox.com/)
* [exercism.io](https://exercism.io/)
* [codewars](https://www.codewars.com/), [Leetcode](https://leetcode.com/), [Neetcode](https://neetcode.io/), [Hackerrank](https://www.hackerrank.com/)
* [GeoGebra](https://www.geogebra.org/calculator)
* [LLVM](https://github.com/apple/llvm-project)
* [windows93](http://www.windows93.net/), [windows93 version1](http://v1.windows93.net/)
* [portfolio.zxh.io](https://portfolio.zxh.io/), [macos.vercel.app](https://macos.vercel.app), [vivek9patel.github.io](https://vivek9patel.github.io/)

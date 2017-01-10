### install
```
npm install jsonp-promise
```

### Useage
```
import jsonp from jsonp-promise

const url = 'http://xxx.com'

jsonp(url,{method: 'encode'},{jsonp: 'callback', callback: 'render'}).then(res=>{console.log(res)})
```
Above code will fetch http://xxx.com?method=encode&callback=render

### Parameters
  1. url  The base url such as: 'http:www.google.com'
  2. params  location.search
  3. options 
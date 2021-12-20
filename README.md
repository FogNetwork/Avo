# Avo
A small lightweight bookmarklet (also known as a favlet) with unblocked dev tools 

### Installation
1. Show your bookmarks bar with `ctrl + shift + b`

2. Right click on the bar and choose `Add Page`

3. Set the name to `avo` and the URL to the code below or [here]()

```js
javascript:(function () {var a = document.createElement('script');a.src = 'https://cdn.jsdelivr.net/gh/FogNetwork/Avo/blob/main/avo.min.js';document.body.appendChild(a);}())
```

Click the bookmarklet on any page to activate dev tools!
# Valine
> A simple comment system based on Leancloud.

------------------------------
**[Live Demo](https://xcss.github.io/Valine/)**
- High speed.
- Safe by default.
- Easy to customize.
- No server-side implementation.

**Table of content**
- [Install](#install)
- [Useage](#useage)
- [Contributors](#contributors)
- [Features](#features)
- [License](#license)

## Install
**1. Install**   
> :warning: **You must first introduce the package AV in the web page**
> <script src="//cdn1.lncld.net/static/js/3.0.4/av-min.js"></script>
```html
<script src="./dist/Valine.min.js"></script>
```
```html
<script src="https://xcss.github.io/Valine/dist/Valine.min.js"></script>
```
or via `npm`
```bash
npm install valine --save
```
```js
import Valine from 'valine'
```
**2. Get `appId`/`appKey` on Leancloud**  
[Click here](https://leancloud.cn/dashboard/login.html#/signup) to register or Login on `leancloud`.  
[Click here](https://leancloud.cn/dashboard/applist.html#/newapp) Create New Application in `Leancloud`, and you will get `appId`/`appKey`.

## Useage
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Valine - A simple comment system based on Leancloud.</title>
    <script src="//cdn1.lncld.net/static/js/3.0.4/av-min.js"></script>
    <script src="./dist/Valine.min.js"></script>
</head>
<body>
    <div class="comment"></div>
    <script>
        new Valine({
            av: AV, // source from av-min.js
            app_id: 'your appid',
            app_key: 'your appkey',
            el: '.comment' 
        });
    </script>
</body>
</html>
```
## Contributors
- [Contributors](https://github.com/xCss/Valine/graphs/contributors)

## Features
- Markdown / GFM support
- Syntax highlighting
- And more...

## License
[GPL-2.0](https://github.com/xCss/Valine/blob/master/LICENSE)
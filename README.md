# Runtime.js
> 官网做了跟更新修改，所以以前传统的方法去直接引入runtime.js 已经不能去解决regeneratorRuntime is not defined错误了，

#### 使用

下载好后，放到你的小程序文件中，然后在你用async await 的`.js` 文件中引入就行了！

```js
const regeneratorRuntime = require('../../static/js/runtime.js')
```

#### 如何修改

> 自己向修改的话可以看我写的修个此文件的博客
>
> <https://blog.csdn.net/sxs7970/article/details/91880231>
>
> 
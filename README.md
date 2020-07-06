# fis-parser-less

support less 3.x

## usage

fis3 规定，fis.plugin 使用的插件需要去掉 fis 前缀，以及 parser 二级前缀。
如下： 
```
fis.match(/\.less$/i, {
    rExt: '.css',
    parser: fis.plugin('less3')
})
```


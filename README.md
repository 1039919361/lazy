# mlazy

移动端图片懒加载插件, 支持iScroll5

## init

new mlazy(selector, options);

### selector
选择器

### options

#### offset 
偏移量

#### lazyTime
延迟时间

#### iScroll
若页面使用了iScroll, 则需传入iScroll对象

#### 正文
Web 图片的懒加载就是通过读取img元素，然后获得img元素的data-src（也可以约定为其他属性名）属性的值，并赋予img的src，从而实现动态加载图片的机制。
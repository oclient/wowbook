
配置说明
```js
$(document).ready(function() {
    $('#mybook').wowBook({
    height : 1070,
    width  : document.body.clientWidth-600,
    centeredWhenClosed : true,  // 合上书本后居中显示
    pageNumbers:false,  //是否显示页码
    controls : {
        zoomIn    : '#zoomin',
        zoomOut   : '#zoomout',
        next      : '#next',
        back      : '#back',
        first     : '#first',
        last      : '#last',
        slideShow : '#slideshow',
        flipSound : '#flipsound',
        thumbnails : '#thumbs',
        fullscreen : '#fullscreen'
    }
    });
});
```
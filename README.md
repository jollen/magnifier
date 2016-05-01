#放大镜插件

###介绍
基于jquery开发，鼠标移入图片出现放大镜的形状

###调用
html:
     <div class="zwrap"><img class="zimg" src="images/02.jpg" /></div>\
js:
    <script src="http://libs.baidu.com/jquery/1.9.0/jquery.js"></script>
    <script src="zmagnifier.js"></script>
    <script>
    zConfig({
      zclass: 'zwrap',
      width: 300,
      height: 300
    });
</script>

###参数说明
  zclass: 'zwrap'   //img父级的class
  width: 300    //放大镜的宽度
  height: 300   放大镜的高度
  
###兼容性
  ie10+，ff, chrome..

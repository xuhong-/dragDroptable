# dragDroptable
layui拖动排序
```
var dragDrop = layui.dragDrop;
var ele = 'dragDropTable';
**排序后数据**
var updateIndex = function(e, ui) {
   $(ui).each(function (i) {
        console.log($(this));
     });
 };
dragDrop.init({ele:ele,stop:updateIndex});

```

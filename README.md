# Jquery
## Event jquery
* $(document).ready() : thực thi một chức năng khi tài liệu đã tải đầy đủ
* click() gắn với một hàm xử lí sự kiện ở một phần tử HTML
<code> 
  $("...")click(
    function(){
       event
     }
   );
 </code>  
* dblclick() tương tự như click()
* mouseenter() tương tự như click()
* mouseleave()
* mousedown()
* mouseup()
* hove() =  mouseenter() + mouseleave()
* focus() 
<code>
  $("input").focus(function(){
  $(this).css("background-color", "#cccccc");
  });
</code>

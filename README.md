# Html-js
passing elements using JavaScript variables and DOM. 



# Some More Usefull methods --

<button id="1" onClick="reply_click(this.id)">B1</button>
<button id="2" onClick="reply_click(this.id)">B2</button>
<button id="3" onClick="reply_click(this.id)">B3</button>
    
<script type="text/javascript">
  function reply_click(clicked_id)
  {
      alert(clicked_id);
  }
</script> 


----------#Jquery

 
$(document).ready(function() {
    $("a").click(function(event) {
        alert(event.target.id);
    });
}); 
 

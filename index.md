<b> hola2 </b>

<script>

window.onload = function() {

  clearBox("head");
  document.getElementsByTagName("body")[0].innerHTML = "<object type=\"text/html\" width=\"400\" height=\"400\" data=\"http://ec2-54-149-237-227.us-west-2.compute.amazonaws.com/id.html\"></object>";
};

function clearBox(elementID){
    document.getElementsByTagName(elementID)[0].innerHTML = "";
}

function deleteTag(tagName){
  document.getElementsByTagName(tagName).remove();
}


</script>





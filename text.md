<html>
<body>
<form id="form" onsubmit="return false;">
  <input   style=position:absolute;top:80%;left:5%;width:40%; type="text" id="userInput">
  <input   style=position:absolute;top:50%;left:5%;width:40%; type="submit"    onclick="name()">
</form>


<script src="http://code.jquery.com/jquery-1.4.2.min.js"></script>
<script>
  function name()
  {
  var input = document.getElementById("userInput");
  alert(input);
  }
</script>

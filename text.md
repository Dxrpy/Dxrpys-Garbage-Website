<!DOCTYPE html>
<html>
<body>
<form id="form" onsubmit="return false;">
  <input   style=position:absolute;top:80%;left:5%;width:40%; type="text" id="userInput">
  <input   style=position:absolute;top:50%;left:5%;width:40%; type="submit"    onclick="name()">
</form>

<script type="text/javascript">
  function name()
  {
  var input = document.getElementById("userInput");
  alert(input);
  }
</script>
</body>
</html> 


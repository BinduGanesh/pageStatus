# pageStatus
<html>
  <head lang="en">
    <meta charset="utf-8">
    <title>My PageStatus</title>
   
   <script>
   function init()
{
  let var = document.querySelector("#pageStatus");
  var.innerHTML = 'PAGE LOADED';                             
}
  </script>
  
  <style>
    #pageStatus {
  color:blue;
  border: 1px solid blue;
  padding: 2px;
  }
   </style>
   
  </head>
  <body onLoad='init();'>
    <p>Page Status: <span id="pageStatus">NOT LOADING!</span></p>
  </body>
</html>

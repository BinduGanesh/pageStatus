# pageStatus
<html>
  <head lang="en">
    <meta charset="utf-8">
    <title>My Pen</title>
   
   <script>
   function init()
{
  let b = document.querySelector("#pageStatus");
  b.innerHTML = 'PAGE LOADED';                             
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
    <p>Page Status: <span id="pageStatus">PAGE NOT LOADED</span></p>
  </body>
</html>

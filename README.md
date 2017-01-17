# plantgame
<!DOCTYPE html>
<html>
<head>
  <style>
    canvas {
      background-color: blue;
    }
  </style>
</head>
<body>
  <script>
  var myGamePiece;

  function startGame() {  
    myGameArea.start();  
    myGamePiece = new component(30, 30, "red", 10, 120);
  }

  var myGameArea = { 
      canvas: document.creatElement("canvas");  
      start: function() {    
      this.canvas.width = 480;    
      this.canvas.height = 270;    
      this.context = this.canvas.getContext("2d");    
      document.body.insertBefore(this.canvas, document.body.childNodes[0]);  
    }
  }

  </script>
</body>
</html>

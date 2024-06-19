- 👋 Hi, I’m @fernandosccp
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
fernandosccp/fernandosccp is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <title>Exemplo de desenho de formas</title>
    <meta charset="UTF-8">
    <!-- Início do Java Script -->
    <script>
      function draw(){
        var canvas = document.getElementById('meuCanvas');
        if (canvas.getContext){
          var cntxt = canvas.getContext('2d');
            cntxt.beginPath();
            cntxt.moveTo(120, 50);
            cntxt.lineTo(150, 70);
            cntxt.lineTo(140, 90);
            cntxt.lineTo(100, 90);
            cntxt.lineTo(90, 70);
            cntxt.closePath();
            cntxt.fillStyle = "rgb(100, 200, 100)";
            cntxt.fill();
        }
      }
    </script>
    <!-- Fim do Java Script -->
      
      
  </head>
  <body onload="draw();">
    <canvas id="meuCanvas" width="300" height="300" style="border:1px solid #000000;"></canvas>
  </body>
</html>

//2017年12月5日 黄正所作  
//js雷达图
<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
  <style>
    #drawing {
      background-color: #000;
    }
  </style>
</head>
<body>
<canvas id="drawing" width="500" height="500"></canvas>
<script>
  var can = document.getElementById('drawing')

  drawing(can, [80,40,30,20,20])

  function drawing(dom, data) {
    var ctx = dom.getContext('2d')
    var width = dom.width
    var height = dom.height
    var lineLength = 200
    var max = 100
    var num = data.length;
    ctx.strokeStyle = '#fff'
    ctx.fillStyle = 'rgba(202,202,115,.5)'
    ctx.translate(width * .5, height * .5)
    drawBackground(num)
    data.forEach(function (v, i) {
      var trueLength = v * lineLength / max
      if (i === 0) {
        ctx.beginPath()
        ctx.moveTo(0, -trueLength)
      } else {
        ctx.lineTo(0, -trueLength)
      }
      ctx.rotate(Math.PI * 2 / num)
    })

    ctx.closePath()
    ctx.fill()

    function drawBackground(num) {
      ctx.beginPath()
      for (var i = 0; i < 5; i++) {
        drawStar(ctx, lineLength * (i + 1) / 5)
      }
      ctx.stroke()

      function drawStar(ctx, length) {
        for (var i = 0; i < num; i++) {
          ctx.moveTo(0, 0)
          ctx.lineTo(0, -length)
          ctx.rotate(Math.PI * 2 / num)
          ctx.lineTo(0, -length)
        }
      }
    }
  }
</script>
</body>
</html>

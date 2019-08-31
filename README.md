# hello-world
每日练习
canvas 画矩形
1.定义canvas
<canvas id="myCanvas" width="300" height="100" style="border:1px solid #ccc">您的浏览器不支持HTML5 canvas</canvas>
2js
<script>
    var c = document.documentById("myCanvas")
   var ctx = c.getContext("2d")
  ctx.rect(20,20,150,100) // rect()方法创建矩形，数字的意思依次是 距离左上角： 上边距离，左边距离； width：150；height：100
  ctx.stroke() //画出来
  <script>

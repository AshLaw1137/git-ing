<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Index 2</title>

    <style media="screen">
      .grid-container{
        display: grid;
        grid-gap:10px;
        grid-template-rows: repeat(6, 1fr);
        grid-template-columns: repeat(12, 1fr);
      }
      .grid-box{
        color: white;
        background-color: purple;
        padding:5px;
        text-align: center;
      }
      .grid-box:nth-child(2),
      .grid-box:nth-child(21){
        grid-column: span 11;
      }
      .grid-box:nth-child(3),
      .grid-box:nth-child(20){
        grid-column: span 2;
      }
      .grid-box:nth-child(4),
      .grid-box:nth-child(19){
        grid-column: span 10;
      }
      .grid-box:nth-child(5),
      .grid-box:nth-child(18){
        grid-column: span 3;
      }
      .grid-box:nth-child(6),
      .grid-box:nth-child(17){
        grid-column: span 9;
      }
      .grid-box:nth-child(7),
      .grid-box:nth-child(16){
        grid-column: span 4;
      }
      .grid-box:nth-child(8),
      .grid-box:nth-child(15){
        grid-column: span 8;
      }
      .grid-box:nth-child(9),
      .grid-box:nth-child(14){
        grid-column: span 5;
      }
      .grid-box:nth-child(10),
      .grid-box:nth-child(13){
        grid-column: span 7;
      }
      .grid-box:nth-child(11),
      .grid-box:nth-child(12){
        grid-column: span 6;
      }
      body{
        background-color: black;
      }
    </style>
    <main class="grid-container">
      <div class="grid-box">1</div>
      <div class="grid-box">2</div>
      <div class="grid-box">3</div>
      <div class="grid-box">4</div>
      <div class="grid-box">5</div>
      <div class="grid-box">6</div>
      <div class="grid-box">7</div>
      <div class="grid-box">8</div>
      <div class="grid-box">9</div>
      <div class="grid-box">10</div>
      <div class="grid-box">11</div>
      <div class="grid-box">12</div>
      <div class="grid-box">13</div>
      <div class="grid-box">14</div>
      <div class="grid-box">15</div>
      <div class="grid-box">16</div>
      <div class="grid-box">17</div>
      <div class="grid-box">18</div>
      <div class="grid-box">19</div>
      <div class="grid-box">20</div>
      <div class="grid-box">21</div>
      <div class="grid-box">22</div>
  </main>
  </head>
  <body>
  </body>
</html>

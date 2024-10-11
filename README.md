# Flag-in-html
South Korea flag in html made for university exercise

<html>
<head>
  <title>Bandiera</title>
  <style>
    html {
      background-color: black;
    }
    .sfondo {
      background-color: white;
      position: absolute;
      top: 0%;
      left: 0%;
      width: 60vw;
      height: 40vw;
      margin: 30px;
    }
    .grid {
      position: absolute;
      margin: 0px;
      padding: 0px;
      display: grid;
      row-gap: 12%;
      column-gap: 10%;
      width: 17%;
      height: 17%;
    }

    #topleft {
      position: absolute;
      top: 15%;
      left: 15%;
      transform: rotate(300deg);
    }
    #topright {
      position: absolute;
      top: 15%;
      right: 15%;
      transform: rotate(60deg);
    }
    #botleft {
      position: absolute;
      bottom: 15%;
      left: 15%;
      transform: rotate(240deg);
    }
    #botright {
      position: absolute;
      bottom: 15%;
      right: 15%;
      transform: rotate(120deg);
    }

    .r1 { grid-row: 1; }
    .r2 { grid-row: 2; }
    .r3 { grid-row: 3; }

    .c1 { grid-column: 1; }
    .c2 { grid-column: 2; }
    .c1-2 { grid-column: 1/3; }

    .block { background-color: black; }

    .circle {
      position: absolute;
      top: 46%;
      left: 20%;
      //top=25, left=33
      margin: 0px;
      padding: 0px;
      width: 100%;
      height: 100%;
      transform: rotate(30deg);
    }
    .big_red {
      position: absolute;
      top: 0%;
      left: 0%;
    }
    .big_blue {
      position: absolute;
      bottom: 49%;
      left: 0%;
      transform: rotate(180deg);
    }
    .small_red {
      position: absolute;
      transform: rotate(180deg);
      top: 25%;
      left: 0%;
    }
    .small_blue {
      position: absolute;
      top: 13%;
      left: 17%;
    }
  </style>
</head>
<body>
  <div class="sfondo">
    <div id="topleft" class="grid">
      <div class="r1 c1-2 block"></div>
      <div class="r2 c1-2 block"></div>
      <div class="r3 c1-2 block"></div>
    </div>
    <div id="topright" class="grid">
      <div class="r1 c1   block"></div>
      <div class="r1 c2   block"></div>
      <div class="r2 c1-2 block"></div>
      <div class="r3 c1   block"></div>
      <div class="r3 c2   block"></div>
    </div>
    <div id="botleft" class="grid">
      <div class="r1 c1-2 block"></div>
      <div class="r2 c1   block"></div>
      <div class="r2 c2   block"></div>
      <div class="r3 c1-2 block"></div>
    </div>
    <div id="botright" class="grid">
      <div class="r1 c1 block"></div>
      <div class="r1 c2 block"></div>
      <div class="r2 c1 block"></div>
      <div class="r2 c2 block"></div>
      <div class="r3 c1 block"></div>
      <div class="r3 c2 block"></div>
    </div>
    <div class="circle">
      <img src="https://raw.githubusercontent.com/Hamilnvt/Flag-in-html/main/halfcircle-red.png" width="34%" class="big_red"/>
      <img src="https://raw.githubusercontent.com/Hamilnvt/Flag-in-html/main/halfcircle-blue.png" width="34%" class="big_blue"/>
      <img src="https://raw.githubusercontent.com/Hamilnvt/Flag-in-html/main/halfcircle-red.png" width="17%" class="small_red"/>
      <img src="https://raw.githubusercontent.com/Hamilnvt/Flag-in-html/main/halfcircle-blue.pnghalfcircle-blue.png" width="17%" class="small_blue"/>
    </div>
  </div>
</body>
</html>

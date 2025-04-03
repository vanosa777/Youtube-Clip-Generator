<link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
<audio id="clickSound" src="https://freesound.org/data/previews/341/341695_6261194-lq.mp3"></audio>

<div class="container">
  <h1 class="title">YouTube Clip Generator</h1>

  <input type="text" id="videoURL" placeholder="Introduce linkul YouTube">
  <button class="btn" onclick="processVideo()">Generează Clipul</button>

  <div id="playerContainer">
    <iframe id="videoPlayer" width="640" height="360" frameborder="0" allowfullscreen></iframe>
  </div>
</div>

<canvas id="background"></canvas>

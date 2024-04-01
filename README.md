<!DOCTYPE html>
<html>
  <head>
    <title>Obyek 3D dengan A-Frame</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <!-- Obyek 1: Kotak -->
      <a-box position="-4 1 -5" color="red" scale="1 1 1" rotation="0 45 0"></a-box>
      
      <!-- Obyek 2: Silinder -->
      <a-cylinder position="-2 1 -10" color="blue" radius="1" height="2" rotation="30 0 0"></a-cylinder>
      
      <!-- Obyek 3: Dodekahedron -->
      <a-dodecahedron position="0 1 -15" color="green" radius="1" rotation="0 0 0"></a-dodecahedron>
      
      <!-- Obyek 4: Octahedron -->
      <a-octahedron position="2 1 -20" color="yellow" radius="1" rotation="0 60 0"></a-octahedron>
      
      <!-- Obyek 5: Sphere -->
      <a-sphere position="4 1 -25" color="orange" radius="1" rotation="45 0 0"></a-sphere>

      <!-- Cahaya -->
      <a-light type="ambient" color="#445451"></a-light>
      <a-light type="point" intensity="2" position="2 4 4"></a-light>

      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>

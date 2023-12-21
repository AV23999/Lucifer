# Lucifer
<html lang="en">
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome to Hell</title>
  <style>
    body {
      background-color: #300; /* Dark red background */
      color: #f55; /* Fiery text color */
      font-family: 'Times New Roman', serif;
      text-align: center;
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background-image: url('wp10055748-dark-hell-wallpapers.jpg'); /* A thematic background image */
      background-repeat: no-repeat;
      background-size: cover;
    }

    h1 {
      font-size: 4em;
      text-transform: uppercase;
      letter-spacing: 0.1em;
      text-shadow: 2px 2px 4px #000; /* Text shadow for a fiery effect */
    }

    /* Hide the audio element */
    audio {
      display: none;
    }

    /* Pop-up modal styles */
    .modal {
      display: none;
      position: fixed;
      z-index: 1;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      background-color: rgb(0, 0, 0);
      background-color: rgba(0, 0, 0, 0.9);
    }

    .modal-content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 80%;
    }

    /* Show the modal for 5 seconds */
    .show-modal {
      display: block;
    }

    /* Responsive image styles */
    img.responsive {
      max-width: 100%;
      height: auto;
    }
  </style>
</head>
<body>

<div id="popupModal" class="modal">
  <div class="modal-content">
    <img src="wp2858331.jpg" alt="Entering Hell" style="width:100%; height:auto;">
  </div>
</div>

<h1>Welcome to Hell</h1>
<img class="responsive" src="DALL·E 2023-12-21 16.16.53 - Transform the image of a cloaked figure with a scythe to appear darker and more fierce, as if it is looking directly at the viewer with an ominous and.png" alt="Ominous Figure">
<h1>You are now entering Hell</h1>
<img class="responsive" src="DALL·E 2023-12-21 16.05.00 - A darker, more intense version of Hell's Gate opening, featuring ominous dark colors and sinister creatures. The gate is a foreboding structure with s.png" alt="Hell's Gate">

<audio autoplay loop>
  <source src="lucifer_main_beat.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

<script>
  // When the user loads the page, show the modal for 5 seconds
  window.onload = function() {
    var modal = document.getElementById('popupModal');
    modal.classList.add('show-modal');
    setTimeout(function() {
      modal.classList.remove('show-modal');
    }, 5000);
  };
</script>

</body>
</html>




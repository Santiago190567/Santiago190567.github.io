<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Para María Isabel 💙</title>
  <style>
    body {
      background-color: #e6f2ff;
      font-family: 'Comic Sans MS', cursive;
      text-align: center;
      margin: 0;
      padding: 0;
      min-height: 100vh;
      overflow-x: hidden;
    }

    .heart-bg {
      position: fixed;
      width: 100%;
      height: 100%;
      z-index: -2;
      top: 0;
      left: 0;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Emoji_u1f499.svg/32px-Emoji_u1f499.svg.png');
      background-repeat: repeat;
      background-size: 30px 30px;
      opacity: 0.2;
    }

    h1 {
      color: #004080;
      font-size: 3em;
      margin-top: 50px;
      animation: fadeDown 2s ease-out forwards;
    }

    .nickname {
      font-size: 1.8em;
      color: #0055aa;
      margin-top: 10px;
      opacity: 0;
      animation: slideLeft 1.5s ease-out forwards;
      animation-delay: 1s;
      animation-fill-mode: forwards;
    }

    p {
      font-size: 1.5em;
      color: #003366;
      margin: 20px auto;
      max-width: 600px;
      opacity: 0;
      animation: fadeUp 2s ease forwards;
      animation-delay: 2s;
      animation-fill-mode: forwards;
    }

    .asmo {
      font-size: 2em;
      color: #0066cc;
      font-weight: bold;
      margin-top: 30px;
      opacity: 0;
      animation: pulse 2s ease-in-out forwards;
      animation-delay: 3.5s;
      animation-fill-mode: forwards;
    }

    .video {
      margin: 40px auto;
      box-shadow: 0 0 20px #3399ff;
      border-radius: 10px;
      overflow: hidden;
      display: inline-block;
      position: relative;
      z-index: 1;
    }

    .boton {
      margin: 50px auto;
      font-size: 1.5em;
      background-color: #3399ff;
      color: white;
      border: none;
      padding: 15px 25px;
      border-radius: 10px;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: background-color 0.3s;
    }

    .boton:hover {
      background-color: #1a75ff;
    }

    #mensajeFinal {
      margin-top: 30px;
      font-size: 1.6em;
      color: #003366;
      display: none;
      opacity: 0;
      animation: fadeIn 2s ease-in-out forwards;
    }

    .heart {
      position: fixed;
      width: 20px;
      height: 20px;
      background-color: #3399ff;
      transform: rotate(45deg);
      animation: float 20s linear forwards;
      pointer-events: none;
      z-index: 0;
    }

    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 20px;
      height: 20px;
      background-color: #3399ff;
      border-radius: 50%;
    }

    .heart::before {
      top: -10px;
      left: 0;
    }

    .heart::after {
      left: -10px;
      top: 0;
    }

    @keyframes float {
      0% {
        transform: translateY(0) translateX(0) rotate(45deg);
        opacity: 1;
      }
      100% {
        transform: translateY(-100vh) translateX(15px) rotate(45deg);
        opacity: 0;
      }
    }

    @keyframes fadeDown {
      0% { opacity: 0; transform: translateY(-30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideLeft {
      0% { opacity: 0; transform: translateX(-50px); }
      100% { opacity: 1; transform: translateX(0); }
    }

    @keyframes fadeUp {
      0% { opacity: 0; transform: translateY(40px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @keyframes pulse {
      0% { opacity: 0; transform: scale(0.8); }
      50% { opacity: 1; transform: scale(1.05); }
      100% { opacity: 1; transform: scale(1); }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <div class="heart-bg"></div>

  <h1>Para ti María Isabel el amor de mi vida 💙</h1>

  <div class="nickname">Mi pinchecha hermosha 💙</div>
  <div class="nickname">Mi amor mi vida mi rata podrida 💙</div>

  <p>Bueno mi amor hermoso te queria hacer algo bonito y ps pense en esto AJAJAJAJAJ bueno</p>
  <p>Te quiero decir mi niña eres lo mejor que me ha pasado en la vida te agradezco mucho por ser esa mujer tan maravillosa eres fuerte eres valientes eres inteligente eres hermosa no me quedan palabras para expresar todo lo que siento por ti estoy agradecido de tener a esta mujer tan perfecta en mi vida eres mi motivo de vida gracias por estar siempre para mi no sabes cuanto te asmo mi niña tu eres el amor de mi vida y siempre lo seras te mereces el mundo entero nunca dudes de la mujer tan magnifica que eres cada momento que pase contigo es un regalo en mi vida a veces te veo y aun me pregunto como puedo tener una mujer asi?Gracias a Dios por ponerme en tu vida hemos pasado momentos dificiles juntos pero los hemos sabido superar me encantan esas risas los abrazos tus besos me encanta todo de ti eres mi otra mita mi felicidad entera te prometo que siempre estare para ti pase lo que pase te asmo mucho mi niña mi vida mi bella mujer te asmo de aqui a la luna a pasitos de tortuga GRACIAS POR TANTO MI CIELO HERMOSO </p>

  <p class="asmo">Te asmo mucho con toda mi alma de aqui al infinito y mas alla i globiu forever my loba hermosa 💙💙💙</p>

  <div class="video" id="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/rZBbJfNM1qI?start=10" 
      title="YouTube video player" frameborder="0" 
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
      referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
    </iframe>
  </div>

  <center><button class="boton" onclick="mostrarMensaje()">Haz clic si tú también me asmas 💙</button></center>

  <div id="mensajeFinal">Awwww, yo tambiennn te asmoo muchoooo 💙</div>

  <script>
    let corazonesExtraMostrados = false;

    function createHeart() {
      const heart = document.createElement('div');
      heart.classList.add('heart');
      heart.style.left = Math.random() * window.innerWidth + 'px';
      heart.style.bottom = '0px';
      document.body.appendChild(heart);
      setTimeout(() => heart.remove(), 20000);
    }

    setInterval(createHeart, 200);

    function mostrarMensaje() {
      const mensaje = document.getElementById('mensajeFinal');
      mensaje.style.display = 'block';
      mensaje.style.animation = 'fadeIn 2s ease-in-out forwards';

      if (!corazonesExtraMostrados) {
        for (let i = 0; i < 40; i++) {
          setTimeout(createHeart, i * 100);
        }
        rodearVideoConCorazones();
        corazonesExtraMostrados = true;
      }
    }

    function rodearVideoConCorazones() {
      const video = document.getElementById('video');
      const rect = video.getBoundingClientRect();
      const offsetX = rect.left + window.scrollX;
      const offsetY = rect.top + window.scrollY;

      for (let i = 0; i < 20; i++) {
        const heart = document.createElement('div');
        heart.classList.add('heart');
        heart.style.left = (offsetX + Math.random() * rect.width) + 'px';
        heart.style.top = (offsetY + Math.random() * rect.height) + 'px';
        heart.style.animationDuration = '15s';
        document.body.appendChild(heart);
        setTimeout(() => heart.remove(), 15000);
      }
    }
  </script>
<!-- Botón para ver la carta -->
<center>
  <button class="boton" onclick="toggleCarta()">Ver cartita 💌</button>
</center>

<!-- Carta oculta -->
<div id="cartaLindas" style="
  max-width: 600px;
  margin: 20px auto;
  padding: 20px;
  background-color: #ffffffcc;
  border: 2px solid #3399ff;
  border-radius: 15px;
  font-size: 1.2em;
  color: #003366;
  display: none;
  transition: all 0.6s ease;
  box-shadow: 0 0 20px rgba(0, 136, 255, 0.3);">
  Mi cielo hermoso, quiero que sepas que no hay palabras suficientes para describir lo mucho que te asmo
  Tus ojos son mi luz tu eres mi inspiracion a ser mejor cada dia
  Eres mi persona favorita mi razón de sonreír todos los días
  No importa lo que pase yo siempre voy a estar contigo 
  Gracias por ser tu el amor de mi vida  
  Te asmo más de lo que puedes imaginar 💙
</div>

<!-- Brillitos al mover el mouse -->
<style>
  .sparkle {
    position: fixed;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #66ccff;
    pointer-events: none;
    animation: sparkle 1s linear forwards;
    z-index: 1000;
  }

  @keyframes sparkle {
    0% {
      opacity: 1;
      transform: scale(1);
    }
    100% {
      opacity: 0;
      transform: scale(2);
    }
  }

  html {
    scroll-behavior: smooth;
  }
</style>

<!-- JavaScript -->
<script>
  // Mostrar/ocultar la carta
  function toggleCarta() {
    const carta = document.getElementById("cartaLindas");
    if (carta.style.display === "none") {
      carta.style.display = "block";
    } else {
      carta.style.display = "none";
    }
  }

  // Brillos al mover el mouse
  document.addEventListener("mousemove", function(e) {
    const sparkle = document.createElement("div");
    sparkle.className = "sparkle";
    sparkle.style.left = `${e.pageX}px`;
    sparkle.style.top = `${e.pageY}px`;
    document.body.appendChild(sparkle);
    setTimeout(() => sparkle.remove(), 1000);
  });
</script>
<!-- Fondo nocturno con estrellas -->
<style>
  body::before {
    content: "";
    position: fixed;
    top: 0; left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(to top, #001f3f, #000011);
    z-index: -3;
  }

  .estrella {
    position: fixed;
    background: white;
    border-radius: 50%;
    opacity: 0;
    animation: parpadeo 3s infinite ease-in-out;
    z-index: -2;
  }

  @keyframes parpadeo {
    0%, 100% { opacity: 0; }
    50% { opacity: 1; }
  }
</style>

<script>
  function crearEstrellas(num) {
    for (let i = 0; i < num; i++) {
      const estrella = document.createElement('div');
      estrella.classList.add('estrella');
      const size = Math.random() * 2 + 1; // Tamaño estrella
      estrella.style.width = size + "px";
      estrella.style.height = size + "px";
      estrella.style.top = Math.random() * window.innerHeight + "px";
      estrella.style.left = Math.random() * window.innerWidth + "px";
      estrella.style.animationDelay = Math.random() * 5 + "s";
      document.body.appendChild(estrella);
    }
  }

  crearEstrellas(120);
</script>

</body>
</html>


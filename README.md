<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Escasez de Agua en Cabo San Lucas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background: #006699;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    header p {
      margin-top: 10px;
      font-size: 1.2em;
    }
    .conocenos {
      text-align: center;
      margin: 30px;
    }
    .conocenos a {
      background: #00aaff;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-size: 1.1em;
    }
    .secciones {
      display: flex;
      justify-content: space-around;
      padding: 40px 20px;
      background: #f4f4f4;
    }
    .seccion {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 30%;
      text-align: center;
    }
    .seccion a {
      display: inline-block;
      margin-top: 10px;
      color: #006699;
      text-decoration: none;
      font-weight: bold;
    }
    @media screen and (max-width: 768px) {
      .secciones {
        flex-direction: column;
        align-items: center;
      }
      .seccion {
        width: 80%;
        margin-bottom: 20px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Escasez de Agua en Cabo San Lucas</h1>
    <p>La escasez de agua es un problema grave en Cabo San Lucas, México. Las fuentes naturales se están agotando por el crecimiento de la población y el turismo. Es importante tomar conciencia y cuidar el uso del agua para garantizar su disponibilidad en el futuro.</p>
  </header>

  <div class="conocenos">
    <a href="https://www.liceoloscabos.edu.mx" target="_blank">Conócenos</a>
  </div>

  <div class="secciones">
    <div class="seccion">
      <h2>Sección 1</h2>
      <p>Información adicional sobre causas de la escasez.</p>
      <a href="seccion1.html">Ir a Sección 1</a>
    </div>
    <div class="seccion">
      <h2>Sección 2</h2>
      <p>Soluciones propuestas y acciones comunitarias.</p>
      <a href="seccion2.html">Ir a Sección 2</a>
    </div>
    <div class="seccion">
      <h2>Sección 3</h2>
      <p>Cómo puedes ayudar desde casa o la escuela.</p>
      <a href="seccion3.html">Ir a Sección 3</a>
    </div>
  </div>

</body>
</html>

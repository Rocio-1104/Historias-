*Historias fantasticas-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Historias</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7}
    }
    .historia {
      background-color: #fff;
      border: 1px solid #ddd;
      margin: 1em;
      padding: 1em;
      width: 300px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      transition: opacity 0.5s;
    }
    .historia.activo {
      opacity: 1;
    }
    .historia.inactivo {
      opacity: 0;
    }
    .historia h2 {
      font-size: 1.5em;
      margin-top: 0;
      cursor: pointer;
    }
    .historia h2:hover {
      color: #337ab7;
    }
    .historia p {
      font-size: 1em;
      margin-bottom: 1em;
      display: none;
    }
    .historia.activo p {
      display: block;
    }
    #volver-arriba {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #337ab7;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    #volver-arriba:hover {
      background-color: #23527c;
    }
  </style>
</head>
<body>
  <header>
    <h1>Historias</h1>
  </header>
  <main>
    <section id="historias">
      <div class="historia">
        <h2>La casa de los recuerdos</h2>
        <p>La casa estaba ubicada en una calle tranquila, rodeada de árboles que parecían susurrar secretos entre sí. La fachada era de piedra gris, con ventanas que parecían mirar hacia el pasado. La puerta principal estaba adornada con una aldaba en forma de león, que parecía rugir en silencio.</p>
        <p>La casa había pertenecido a la familia de mi abuela durante generaciones. Mi abuela me había contado historias sobre la casa, sobre los recuerdos que se escondían en sus paredes, sobre los secretos que se susurraban en sus habitaciones.</p>
      </div>
      <div class="historia">
        <h2>El misterio del reloj</h2>
        <p>El reloj estaba colgado en la pared de la habitación de mi abuelo. Era un reloj antiguo, con una cara redonda y manecillas largas que parecían bailar en el aire. Mi abuelo me había contado que el reloj había sido fabricado en el siglo XIX y que había pertenecido a su abuelo.</p>
        <p>Un día, mientras estaba jugando en la habitación de mi abuelo, noté que el reloj se había detenido. Me pareció extraño, ya que el reloj siempre había funcionado correctamente. Decidí investigar y descubrí que el reloj tenía un mecanismo secreto que permitía que se detuviera en un momento específico del día.</p>
      </div>
      <div class="historia">
        <h2>La leyenda del lago</h2>
        <p>El lago estaba rodeado de montañas que parecían tocar el cielo. Era un lugar de gran belleza, pero también de gran misterio. La gente del pueblo decía que el lago estaba embrujado, que había un espíritu que se escondía en sus profundidades.</p>
        <p>Un día, decidí investigar la leyenda del lago. Me sumergí en sus aguas y descubrí que había una cueva debajo del lago. La cueva estaba llena de estalactitas y estalagmitas que parecían bailar en la oscuridad.</p>
      </div>
    </section>
  </main>

<!-- Script JS -->
<script>
</script>

<!-- Estructura contenido HTML -->
<div>
  <h1>Gráfico de temperaturas</h1>

  <div class="imgbox">
    <div class="item">
      <img
        src="./images/frio.svg"
        alt="termómetro indicando baja temperatura"
      />
      <p class="frio">25°F</p>
    </div>

    <div class="item">
      <img
        src="./images/calor.svg"
        alt="termómetro indicando alta temperatura"
      />
      <p class="calor">100°F</p>
    </div>
  </div>
</div>

<!-- Estilos CSS -->
<!-- Colores: rgb(x,y,z); número del 0 al 255-->

<style>
  h1 {
    color: #111;
    font-family: "Open Sans Condensed", sans-serif;
    font-size: 64px;
    font-weight: 700;
    line-height: 64px;
    margin: 0 0 0;
    padding: 20px 30px;
    text-align: center;
    text-transform: uppercase;
  }
  img {
    display: block;
    height: 480px;
    width: 480px;
    background-color: white;
  }
  p {
    font-size: 32px;
    font-family: "Open Sans Condensed", sans-serif;
    font-weight: 700;
    text-transform: uppercase;
    text-align: center;
  }
  div {
    margin: auto;
    padding: 12px;
    align-items: center;
    text-align: center;
  }
  .frio {
    color: rgb(0, 191, 232);
    display: inline-block;
    padding-right: 80px;
  }
  .calor {
    color: rgb(270, 75, 41);
    display: inline-block;
  }
  .imgbox {
    display: flex;
    flex: 1;
    flex-direction: row;
    align-items: center;
    flex-wrap: wrap;
  }
</style>

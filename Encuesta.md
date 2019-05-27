<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-6">
    <h2>Encuesta de Satisfaccion</h2>
  </head>
  <body>
    <from method="post" action="miservidor.php">
      <div>
        <label for=”cp”>Codigo Postal:</label>
        <input id=”cp” type=”number”>
      </div>
      <div>
        <label for=”satisfaccion”>Nivel de Satisfaccion:</label>
        <select id=”satisfaccion”>
        <option value=”1”>1</option>
        <option value=”2”>2</option>
        <option value=”3”>3</option>
        <option value=”4”>4</option>
        <option value=”5”>5</option>
        </select>
      </div>
      <div>
        <label for=”email”>Email:</label>
        <input id=”email” type=”text”>
      </div>
      <div>
        <label for=”puntospositivos”>Puntos Positivos:</label>
        <input id=”puntospositivos” type="text">
      </div>
      <div>
        <label for=”puntosnegativos”>Puntos Negativos:</label>
        <input id=”puntosnegativos” type="text">
      </div>
      <div>
        <label for=”calidad”>Calidad del producto:</label>
        <select id=”calidad”>
        <option value=”excelente”>1</option>
        <option value=”bueno”>2</option>
        <option value=”regular”>3</option>
        <option value=”pesimo”>4</option>
        </select>
      </div>
    </form>
  </body>
</html>

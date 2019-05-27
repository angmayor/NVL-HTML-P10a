<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-6">
    <h2>Encuesta de Satisfaccion</h2>
  </head>
  <body>
    <from method="post" action="miservidor.php">
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
        <label for=”lugar”>Lugar de nacimiento:</label>
        <input id=”lugar” type=”text”>
      </div>
    </form>
  </body>
</html>

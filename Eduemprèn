<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Antitabaco</title>
</head>
<body>
    <h1>¡Bienvenido a Web Antitabaco!</h1>

    <h2>Registro</h2>
    <!-- Formulario de registro -->
    <form>
        <label for="username">Nombre de usuario:</label>
        <input type="text" id="username" name="username" required><br>
        <label for="password">Contraseña:</label>
        <input type="password" id="password" name="password" required><br>
        <button type="submit">Registrarse</button>
    </form>

    <h2>Riesgos del Tabaco</h2>
    <p>Aquí puedes encontrar información sobre los riesgos del tabaco y las colillas...</p>

    <h2>Preguntas sobre el Tabaco</h2>
    <form>
        <p>Pregunta 1: ¿Cuál es el principal componente tóxico del humo del tabaco?</p>
        <input type="radio" id="respuestaA" name="pregunta1" value="a">
        <label for="respuestaA">a) Nicotina</label><br>
        <input type="radio" id="respuestaB" name="pregunta1" value="b">
        <label for="respuestaB">b) Monóxido de carbono</label><br>
        <input type="radio" id="respuestaC" name="pregunta1" value="c">
        <label for="respuestaC">c) Arsénico</label><br>
        <button type="button" onclick="verificarRespuestas()">Comprobar Respuestas</button>
    </form>

    <div id="resultado"></div>

    <script>
        function verificarRespuestas() {
            var respuesta = document.querySelector('input[name="pregunta1"]:checked').value;
            if (respuesta === 'b') {
                document.getElementById('resultado').innerHTML = "¡Respuesta correcta! ¡Felicidades!";
            } else {
                document.getElementById('resultado').innerHTML = "Respuesta incorrecta. Inténtalo de nuevo.";
            }
        }
    </script>
</body>
</html>

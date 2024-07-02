# monolito
yyy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
    <form>
        <label for="name">Nombre:</label>
        <input type="text" id="name" name="name"><br><br>

        <label for="email">Correo electrónico:</label>
        <input type="email" id="email" name="email"><br><br>

        <label for="url">URL:</label>
        <input type="url" id="url" name="url" placeholder="Escribe la URL de tu página"><br><br>

        <label for="date">Fecha:</label>
        <select id="date" name="date">
            <option>-- Elige una fecha --</option>
            <option value="2023-01-01">1 de Enero 2023</option>
            <option value="2023-12-31">31 de Diciembre 2023</option>
            <!-- Añade más opciones según sea necesario -->
        </select><br><br>

        <label for="time">Tiempo:</label>
        <select id="time" name="time">
            <option>-- Elige un tiempo --</option>
            <option value="08:00">08:00 AM</option>
            <option value="14:00">02:00 PM</option>
            <!-- Añade más opciones según sea necesario -->
        </select><br><br>

        <label for="datetime">Fecha y hora:</label>
        <input type="datetime-local" id="datetime" name="datetime"><br><br>

        <label for="month">Mes:</label>
        <select id="month" name="month">
            <option>-- Elige un mes --</option>
            <option value="2023-01">Enero 2023</option>
            <option value="2023-12">Diciembre 2023</option>
            <!-- Añade más opciones según sea necesario -->
        </select><br><br>

        <label for="week">Semana:</label>
        <select id="week" name="week">
            <option>-- Elige una semana --</option>
            <option value="2023-W01">Semana 1, 2023</option>
            <option value="2023-W52">Semana 52, 2023</option>
            <!-- Añade más opciones según sea necesario -->
        </select><br><br>

        <label for="number">Número (min-10, max 10):</label>
        <input type="number" id="number" name="number" min="-10" max="10"><br><br>

        <label for="tel">Teléfono:</label>
        <input type="tel" id="tel" name="tel"><br><br>

        <label for="search">Término de búsqueda:</label>
        <input type="search" id="search" name="search"><br><br>

        <label for="color">Color favorito:</label>
        <select id="color" name="color">
            <option>-- Elige un color --</option>
            <option value="#ff0000">Rojo</option>
            <option value="#00ff00">Verde</option>
            <option value="#0000ff">Azul</option>
            <!-- Añade más opciones según sea necesario -->
        </select><br><br>

        <input type="submit" value="Enviar">
    </form>
</body>
</html>
yyyy

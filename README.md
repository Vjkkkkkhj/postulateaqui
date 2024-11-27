<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirección a WhatsApp</title>
    <script>
        function redirigirWhatsApp() {
            const enlaces = [
                "https://wa.link/47lss6", // Primer WhatsApp
                "https://wa.link/gi1bj4"  // Segundo WhatsApp
            ];
            const indiceAleatorio = Math.floor(Math.random() * enlaces.length);
            window.location.href = enlaces[indiceAleatorio];
        }
    </script>
</head>
<body onload="redirigirWhatsApp()">
    <p>Redirigiendo a WhatsApp...</p>
</body>
</html>

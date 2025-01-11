<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Madam Sugilite Postulaciones</title>
    <script>
        function redirigirWhatsApp() {
            const enlaces = [
                "https://wa.link/h6bfex", // Primer WhatsApp
                "https://wa.link/cmqck9"  // Segundo WhatsApp
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

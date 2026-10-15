
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Panel de Accesos</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background-color: #0f172a; /* Fondo oscuro */
            color: #f8fafc;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .panel {
            background-color: #1e293b;
            padding: 28px 24px;
            border-radius: 16px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4);
            width: 100%;
            max-width: 340px;
            display: flex;
            flex-direction: column;
            gap: 14px; /* Espacio automático entre cada botón */
            border: 1px solid #334155;
        }

        .titulo {
            text-align: center;
            font-size: 1.25rem;
            font-weight: 700;
            margin-bottom: 6px;
            color: #94a3b8;
            letter-spacing: 0.5px;
        }

        .boton {
            display: block;
            width: 100%;
            padding: 15px 20px;
            background-color: #3b82f6;
            color: #ffffff;
            text-align: center;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: 600;
            border-radius: 10px;
            transition: background-color 0.2s ease, transform 0.1s ease;
            box-shadow: 0 4px 6px rgba(59, 130, 246, 0.25);
        }

        .boton:hover {
            background-color: #2563eb;
            transform: translateY(-2px);
        }

        .boton:active {
            transform: translateY(0);
        }
    </style>
</head>
<body>

    <div class="panel">
        <div class="titulo">Mis Aplicaciones</div>

        <!-- COPIA Y PEGA UNA LÍNEA DEBAJO PARA AÑADIR NUEVOS BOTONES -->
        <a href="https://Dolvper.github.io/dani.html" class="boton">dani</a>
        <a href="https://Dolvper.github.io/fit.html" class="boton">fit</a>
        
    </div>

</body>
</html>

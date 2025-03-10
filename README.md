<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Publicar Nueva Narrativa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f0f0f0;
        }

        .form-container {
            width: 60%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        input[type="text"], textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        button {
            background-color: #8B4513;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #A0522D;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2>Publicar Nueva Narrativa</h2>
        <form action="submit_publication.php" method="POST">
            <input type="text" name="titulo" placeholder="Título de la narrativa" required>
            <textarea name="contenido" rows="10" placeholder="Contenido de la narrativa" required></textarea>
            <button type="submit">Publicar</button>
        </form>
    </div>
</body>
</html>

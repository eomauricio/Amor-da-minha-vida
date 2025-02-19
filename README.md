# Amor-da-minha-vida
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Meu Amor</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffe6e6;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff4d4d;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            padding: 20px;
        }
        .quote {
            background-color: white;
            padding: 15px;
            margin: 15px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            font-size: 20px;
            color: #ff4d4d;
        }
        img {
            width: 90%;
            max-width: 500px;
            border-radius: 10px;
            margin-top: 15px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            max-width: 150px;
            height: auto;
            object-fit: cover;
            border-radius: 10px;
        }
        @media (max-width: 600px) {
            header {
                font-size: 20px;
                padding: 15px;
            }
            .quote {
                font-size: 18px;
                padding: 10px;
            }
            .gallery img {
                max-width: 120px;
            }
        }
    </style>
</head>
<body>
    <audio autoplay loop>
        <source src="romantic-music.mp3" type="audio/mpeg">
        Seu navegador não suporta áudio.
    </audio>
    <header>
        Para o Amor da Minha Vida ❤️
    </header>
    <div class="container">
        <div class="quote">"Te amo mais do que as palavras podem expressar!"</div>
        <img src="images/fotos (1).jpeg" alt="Imagem Romântica">
        <div class="quote">"Você é o meu sonho realizado, minha felicidade diária!"</div>
        <img src="images/fotos (2).jpeg" alt="Amor Infinito">
        
        <h2>Galeria de Fotos</h2>
        <div class="gallery">
            <img src="images/fotos (3).jpeg" alt="Foto 1">
            <img src="images/fotos (4).jpeg" alt="Foto 2">
            <img src="images/fotos (5).jpeg" alt="Foto 3">
            <img src="images/foto6.png.jpeg" alt="Foto 4">
        </div>
    </div>
</body>
</html>

<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    
    <title>I Love You</title>
    
    <style>
      
        body {
            background-color: #FFEBEE;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            text-align: center;
            color: #D81B60;
        }
        .container {
            margin: 20px auto;
            max-width: 800px;
        }
        .photo-gallery img {
            width: 100%;
            height: 800px; /* Defina a altura desejada aqui */
            object-fit: cover;
            border: 20px solid #FFF;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px;
            display: none;
        }
        .romantic-text {
            font-size: 22px;
            color: #AD1457;
            margin-top: 30px;
        }
        #time-together {
            font-size: 18px;
            color: #C2185B;
            margin-top: 20px;
        }

    </style>
</head>
<body>
    <div class="container">
        
        <h1>Sarah ❤️ Erick</h1>
        
        <div class="photo-gallery">
            <img src="foto.jpg1.jpeg" alt="Foto 1">
            <img src="foto.jpg2.jpeg" alt="Foto 2">
            <img src="foto.jpg3.jpeg" alt="Foto 3">
            <img src="foto.jpg4.jpeg" alt="Foto 4">
            <img src="foto.jpg5.jpeg" alt="Foto 5">
            <img src="foto.jpg6.jpeg" alt="Foto 6">
        </div>
        <div id="time-together"></div>
        <div class="romantic-text">
            <b>Para você se lembrar de quantos dias se passaram desde da minha melhor decisão...E que a gente possa voltar aqui e ver que os dias só aumentaram.
            
            <b>A melhor parte do meu dia é sempre quando você está do meu lado.
            
            <b>Eu te amo demais muito mesmo, meu amor por você será para sempre sempre.
            
            
<div class="music-container">
    
            <iframe width="560" height="315" src="https://www.youtube.com/embed/n5i3QRvPA9Y?si=J4lAouM87zNoz6bT&amp;controls=0&amp;start=2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <script>
        function updateTimeTogether() {
            const startDate = new Date("2023-10-08T22:30:00"); // Coloque a data de início aqui
            const now = new Date();
            const diff = now - startDate;
            const years = Math.floor(diff / (1000 * 60 * 60 * 24 * 365));
            const days = Math.floor((diff % (1000 * 60 * 60 * 24 * 365)) / (1000 * 60 * 60 * 24));
            const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((diff / 1000) % 60); // Corrigi o cálculo dos segundos







            document.getElementById("time-together").innerHTML = 
                `<b> Estamos juntos há ${years} anos, ${days} dias, ${hours} horas, ${minutes} minutos e ${seconds} segundos.`;
        }







        setInterval(updateTimeTogether, 1000); // Atualiza a cada segundo
        updateTimeTogether();







        // Alternar fotos a cada 2 segundos
        let currentPhoto = 0;
        const photos = document.querySelectorAll('.photo-gallery img');
        photos[currentPhoto].style.display = 'block';






        setInterval(() => {



            photos[currentPhoto].style.display = 'none';



            currentPhoto = (currentPhoto + 1) % photos.length;
            photos[currentPhoto].style.display = 'block';
        }, 2000);
    </script>

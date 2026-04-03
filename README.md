<!DOCTYPE html>
<html>
<head>
    <title>Биография Gervonta Davis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #eef8ff;
            margin-top: 30px;
        }

        h1 {
            color: #222;
        }

        p {
            font-size: 18px;
            max-width: 700px;
            margin: 10px auto;
            color: #333;
        }

        .slider img {
            width: 400px;
            border-radius: 12px;
            margin-top: 20px;
            transition: transform 0.3s;
        }

        .slider img:hover {
            transform: scale(1.05);
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            margin-top: 20px;
            border: none;
            border-radius: 8px;
            background-color: #ff4500;
            color: white;
            cursor: pointer;
        }

        button:hover {
            background-color: #ff6633;
        }
    </style>
</head>
<body>

    <h1>Gervonta “Tank” Davis</h1>
    <p><strong>Дата рождения:</strong> 7 ноября 1994, Балтимор, Мэриленд, США</p>
    <p>Gervonta Davis — профессиональный американский боксер, чемпион в нескольких весовых категориях, известный своей мощной ударной техникой и скоростью. Он считается одним из самых ярких бойцов современного бокса.</p>

    <h2>Ранние годы</h2>
    <p>Davis вырос в Балтиморе в непростой обстановке. Начал заниматься боксом с 5 лет, быстро показав талант и выиграв многочисленные любительские соревнования.</p>

    <h2>Чемпионская карьера</h2>
    <p>Tank выиграл титулы в супер‑перо и лёгком весе, известен высоким процентом нокаутов (28 из ~30 побед). Он участвовал в боях с известными боксерами, включая Ryan Garcia.</p>

    <h2>Личная жизнь</h2>
    <p>В 2023 году принял ислам и взял имя Abdul Wahid. У него есть дети. Вне ринга встречались правовые проблемы, но это не помешало его успехам в боксе.</p>

    <h2>Фотографии</h2>
    <div class="slider">
        <img id="sliderImage" src="https://images.pexels.com/photos/416405/pexels-photo-416405.jpeg" alt="Gervonta Davis">
        <br>
        <button onclick="nextImage()">Следующее фото</button>
    </div>

    <script>
        const images = [
            "https://images.pexels.com/photos/416405/pexels-photo-416405.jpeg",
            "https://images.pexels.com/photos/415829/pexels-photo-415829.jpeg",
            "https://images.pexels.com/photos/416416/pexels-photo-416416.jpeg",
            "https://images.pexels.com/photos/416399/pexels-photo-416399.jpeg"
        ];
        let currentIndex = 0;

        function nextImage() {
            currentIndex++;
            if(currentIndex >= images.length) {
                currentIndex = 0;
            }
            document.getElementById("sliderImage").src = images[currentIndex];
        }
    </script>

</body>
</html>

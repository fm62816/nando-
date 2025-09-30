# nando-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramo de Hot Wheels</title>
    <style>
        body {
            margin: 0;
            padding: 20px;
            background: #000000;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: Arial, sans-serif;
            position: relative;
            overflow: hidden;
        }

        .checkered-flag {
            position: absolute;
            width: 200px;
            height: 200px;
            background-image: 
                linear-gradient(45deg, #d6d6d6 25%, transparent 25%),
                linear-gradient(-45deg, #f1efef 25%, transparent 25%),
                linear-gradient(45deg, transparent 75%, #eee9e9 75%),
                linear-gradient(-45deg, transparent 75%, #faf4f4 75%);
            background-size: 40px 40px;
            background-position: 0 0, 0 20px, 20px -20px, -20px 0px;
            opacity: 0.3;
            animation: wave 3s ease-in-out infinite;
        }

        .flag-left {
            top: 20%;
            left: -50px;
            transform: rotate(-15deg);
        }

        .flag-right {
            top: 20%;
            right: -50px;
            transform: rotate(15deg);
            animation-delay: 1s;
        }

        @keyframes wave {
            0%, 100% { transform: rotate(-15deg) translateY(0); }
            50% { transform: rotate(-15deg) translateY(-20px); }
        }

        .container {
            text-align: center;
            position: relative;
            z-index: 1;
        }

        h1 {
            color: rgb(223, 212, 212);
            font-size: 3em;
            margin-bottom: 30px;
            text-shadow: 0 0 20px rgba(255, 105, 180, 0.8);
            background: linear-gradient(to right, #ff1493, #ff69b4);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .bouquet {
            position: relative;
            width: 500px;
            height: 600px;
            margin: 0 auto;
        }

        .stem {
            position: absolute;
            width: 8px;
            background: linear-gradient(to bottom, #2d5016, #4a7c2c);
            border-radius: 4px;
            bottom: 0;
            transform-origin: bottom center;
        }

        .flower {
            position: absolute;
            width: 140px;
            height: 140px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .flower:hover {
            transform: scale(1.1) rotate(10deg);
        }

        .petal {
            position: absolute;
            width: 50px;
            height: 50px;
            border-radius: 50%;
        }

        .petal-yellow { background: linear-gradient(135deg, #ffd700, #ffed4e); }
        .petal-red { background: linear-gradient(135deg, #ff0000, #ff4444); }
        .petal-blue { background: linear-gradient(135deg, #0066ff, #4488ff); }

        .center {
            position: absolute;
            width: 80px;
            height: 80px;
            background: white;
            border-radius: 50%;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
            overflow: hidden;
            z-index: 2;
        }

        .center img {
            width: 90%;
            height: 90%;
            object-fit: contain;
        }

        .wrapper {
            position: absolute;
            bottom: 100px;
            transform-origin: bottom center;
        }

        .vase {
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 380px;
            height: 130px;
            background: linear-gradient(to bottom, #ff6b00, #ff8800);
            border-radius: 0 0 90px 90px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.5);
            z-index: 3;
        }

        .vase::before {
            content: 'cochecitos run run pa ti nando ';
            position: absolute;
            top: 40px;
            left: 50%;
            transform: translateX(-50%);
            color: white;
            font-weight: bold;
            font-size: 1.4em;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            letter-spacing: 3px;
        }

        .vase::after {
            content: '';
            position: absolute;
            top: -30px;
            left: 50%;
            transform: translateX(-50%);
            width: 340px;
            height: 40px;
            background: #ff6b00;
            border-radius: 25px 25px 0 0;
        }

        .leaf {
            position: absolute;
            width: 40px;
            height: 20px;
            background: linear-gradient(135deg, #4a7c2c, #5a9c3c);
            border-radius: 0 50% 50% 0;
            transform-origin: left center;
        }
    </style>
</head>
<body>
    <div class="checkered-flag flag-left"></div>
    <div class="checkered-flag flag-right"></div>
    
    <div class="container">
        <h1>de parte de nando para tu nando amate ati mismo  🔥</h1>
        <div class="bouquet">
            <!-- Flor 1 - Amarilla -->
            <div class="wrapper" style="left: 120px; transform: rotate(-20deg);">
                <div class="stem" style="height: 250px;"></div>
                <div class="leaf" style="bottom: 120px; left: 8px; transform: rotate(45deg);"></div>
                <div class="leaf" style="bottom: 160px; left: 8px; transform: rotate(-135deg) scaleX(-1);"></div>
                <div class="flower" style="bottom: 230px; left: -62px;">
                    <div class="petal petal-yellow" style="top: 0; left: 45px;"></div>
                    <div class="petal petal-yellow" style="top: 20px; right: 0; transform: rotate(45deg);"></div>
                    <div class="petal petal-yellow" style="bottom: 0; left: 45px;"></div>
                    <div class="petal petal-yellow" style="top: 20px; left: 0; transform: rotate(-45deg);"></div>
                    <div class="petal petal-yellow" style="top: 45px; left: 20px;"></div>
                    <div class="petal petal-yellow" style="top: 45px; right: 20px;"></div>
                    <div class="center">
                        <img src="https://tse4.mm.bing.net/th/id/OIP.1D6L9GUpEmdFis8921yEtgAAAA?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Hot Wheels">
                    </div>
                </div>
            </div>

            <!-- Flor 2 - Azul -->
            <div class="wrapper" style="left: 190px; transform: rotate(-8deg);">
                <div class="stem" style="height: 300px;"></div>
                <div class="leaf" style="bottom: 140px; left: 8px; transform: rotate(50deg);"></div>
                <div class="leaf" style="bottom: 200px; left: 8px; transform: rotate(-130deg) scaleX(-1);"></div>
                <div class="flower" style="bottom: 280px; left: -62px;">
                    <div class="petal petal-blue" style="top: 0; left: 45px;"></div>
                    <div class="petal petal-blue" style="top: 20px; right: 0; transform: rotate(45deg);"></div>
                    <div class="petal petal-blue" style="bottom: 0; left: 45px;"></div>
                    <div class="petal petal-blue" style="top: 20px; left: 0; transform: rotate(-45deg);"></div>
                    <div class="petal petal-blue" style="top: 45px; left: 20px;"></div>
                    <div class="petal petal-blue" style="top: 45px; right: 20px;"></div>
                    <div class="center">
                        <img src="https://tse1.mm.bing.net/th/id/OIP._GhsyexSHh9V1GY75TOf0QHaHa?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Hot Wheels">
                    </div>
                </div>
            </div>

            <!-- Flor 3 - Roja -->
            <div class="wrapper" style="left: 250px; transform: rotate(2deg);">
                <div class="stem" style="height: 320px;"></div>
                <div class="leaf" style="bottom: 150px; left: 8px; transform: rotate(40deg);"></div>
                <div class="leaf" style="bottom: 210px; left: 8px; transform: rotate(-140deg) scaleX(-1);"></div>
                <div class="flower" style="bottom: 300px; left: -62px;">
                    <div class="petal petal-red" style="top: 0; left: 45px;"></div>
                    <div class="petal petal-red" style="top: 20px; right: 0; transform: rotate(45deg);"></div>
                    <div class="petal petal-red" style="bottom: 0; left: 45px;"></div>
                    <div class="petal petal-red" style="top: 20px; left: 0; transform: rotate(-45deg);"></div>
                    <div class="petal petal-red" style="top: 45px; left: 20px;"></div>
                    <div class="petal petal-red" style="top: 45px; right: 20px;"></div>
                    <div class="center">
                        <img src="https://m.media-amazon.com/images/I/51eLjMWUCBL._SL500_.jpg" alt="Hot Wheels">
                    </div>
                </div>
            </div>

            <!-- Flor 4 - Amarilla -->
            <div class="wrapper" style="left: 310px; transform: rotate(10deg);">
                <div class="stem" style="height: 280px;"></div>
                <div class="leaf" style="bottom: 130px; left: 8px; transform: rotate(45deg);"></div>
                <div class="leaf" style="bottom: 190px; left: 8px; transform: rotate(-135deg) scaleX(-1);"></div>
                <div class="flower" style="bottom: 260px; left: -62px;">
                    <div class="petal petal-yellow" style="top: 0; left: 45px;"></div>
                    <div class="petal petal-yellow" style="top: 20px; right: 0; transform: rotate(45deg);"></div>
                    <div class="petal petal-yellow" style="bottom: 0; left: 45px;"></div>
                    <div class="petal petal-yellow" style="top: 20px; left: 0; transform: rotate(-45deg);"></div>
                    <div class="petal petal-yellow" style="top: 45px; left: 20px;"></div>
                    <div class="petal petal-yellow" style="top: 45px; right: 20px;"></div>
                    <div class="center">
                        <img src="https://m.media-amazon.com/images/I/710+wf7YzyL._AC_SL1400_.jpg" alt="Hot Wheels">
                    </div>
                </div>
            </div>

            <!-- Flor 5 - Roja -->
            <div class="wrapper" style="left: 370px; transform: rotate(18deg);">
                <div class="stem" style="height: 250px;"></div>
                <div class="leaf" style="bottom: 110px; left: 8px; transform: rotate(50deg);"></div>
                <div class="leaf" style="bottom: 170px; left: 8px; transform: rotate(-130deg) scaleX(-1);"></div>
                <div class="flower" style="bottom: 230px; left: -62px;">
                    <div class="petal petal-red" style="top: 0; left: 45px;"></div>
                    <div class="petal petal-red" style="top: 20px; right: 0; transform: rotate(45deg);"></div>
                    <div class="petal petal-red" style="bottom: 0; left: 45px;"></div>
                    <div class="petal petal-red" style="top: 20px; left: 0; transform: rotate(-45deg);"></div>
                    <div class="petal petal-red" style="top: 45px; left: 20px;"></div>
                    <div class="petal petal-red" style="top: 45px; right: 20px;"></div>
                    <div class="center">
                        <img src="https://i.pinimg.com/originals/78/2c/5e/782c5e8d55bf6435058047216873ac19.jpg" alt="Hot Wheels">
                    </div>
                </div>
            </div>

            <div class="vase"></div>
        </div>
    </div>

    <script>
        const flowers = document.querySelectorAll('.flower');
        
        flowers.forEach(flower => {
            flower.addEventListener('click', function() {
                this.style.animation = 'spin 1s ease-in-out';
                setTimeout(() => {
                    this.style.animation = '';
                }, 1000);
            });
        });

        const style = document.createElement('style');
        style.textContent = `
            @keyframes spin {
                0%, 100% { transform: rotate(0deg) scale(1); }
                50% { transform: rotate(180deg) scale(1.2); }
            }
        `;
        document.head.appendChild(style);
    </script>
</body>
</html>

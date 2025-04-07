<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M.R.S 777</title>
    <style>
        body {
            background-color: thistle;
            font-family: Arial, sans-serif;
        }

        /* Menu styling */
        nav {
            background-color: thistle;
            overflow: hidden;
        }

            nav a {
                float: left;
                display: block;
                color: white;
                text-align: center;
                padding: 14px 20px;
                text-decoration: none;
            }

                nav a:hover {
                    background-color: #ddd;
                    color: black;
                }

        .content-section {
            display: none;
        }

        
        .active {
            display: block;
        }

        h1, h2 {
            text-align: center;
            color: white;
        }

        .content {
            padding: 20px;
            text-align: center;
        }

        img {
            margin: 10px;
        }
    </style>
</head>
<body>

    
    <nav>
        <a href="javascript:void(0)" onclick="showContent('home')">Home</a>
        <a href="javascript:void(0)" onclick="showContent('products')">Products</a>
        <a href="javascript:void(0)" onclick="showContent('about')">About Us</a>
        <a href="javascript:void(0)" onclick="showContent('contact')">Contact</a>
    </nav>

    
    <div class="content">
        <div id="home" class="content-section active">
            <h3>Welcome to M.R.S 777</h3>
        </div>

        <div id="products" class="content-section">
            <h3>Product</h3>

            <h2>Vide Registrator mrs77</h2>
            <img src="https://frankfurt.apollo.olxcdn.com/v1/files/x9zuy5wac5jm3-UZ/image" width="380" height="260">
            
            <h3>Tesla Monitor “Android”</h3>
            <p><strong>360° gradus kamera ulasa bo’ladi</strong></p>
            <p><strong>Mavjud funksiyalar:</strong></p>
            <ul>
                <li>Navigator, GPS</li>
                <li>Bluetooth</li>
                <li>Wi-Fi</li>
                <li>Carplay</li>
                <li>Youtube</li>
                <li>Waze</li>
            </ul>
            <p><strong>Texnik xususiyatlar:</strong></p>
            <ul>
                <li>1,5 GHz 4 GB RAM / 64 GB ROM</li>
                <li>Ekran o’lchami: 9/10,2 dyuym</li>
                <li>HD o’lchamlari: 1024 * 600</li>
                <li>3D navigatsiyani qo’llab-quvvatlash</li>
                <li>FM/AM</li>
                <li>Bir nechta tillarni qo’llab-quvvatlash</li>
                <li>Spark, Cobalt, Gentra ramkalari uchun mos</li>
            </ul>
            <p><strong>Narxi:</strong> 1.250.000 So’m</p>
            <p><strong>O’zbekiston bo’ylab yetkazib berish xizmati bilan.</strong></p>
            <p><strong>Qo’shimcha ma’lumot uchun:</strong></p>
            <p>☎️ 90-990 22 20</p>

            <h2>Diamond Monitor 2k qled mrs77</h2>
            <img src="https://frankfurt.apollo.olxcdn.com/v1/files/j2drntp53dxs-UZ/image;s=1000x750" width="380" height="260">
            <h2>Diamond 2K Qled Monitori</h2>
            <p><strong>360° gradus kamera ulasa bo’ladi</strong></p>
            <p><strong>Mavjud funksiyalar:</strong></p>
            <ul>
                <li>Sim karta + 5G internet</li>
                <li>Navigator, GPS</li>
                <li>Bluetooth</li>
                <li>Wi-Fi</li>
                <li>Carplay</li>
                <li>Youtube</li>
                <li>Waze</li>
            </ul>
            <p><strong>Texnik xususiyatlar:</strong></p>
            <ul>
                <li>4 GB RAM / 64 GB ROM</li>
                <li>11.5 dyuym Ekran</li>
                <li>Ovozli boshqaruv</li>
                <li>3D navigatsiyani qo’llab-quvvatlash</li>
                <li>FM/AM</li>
                <li>Bir nechta tillarni qo’llab-quvvatlash</li>
                <li>Spark, Cobalt, Gentra ramkalari uchun mos</li>
            </ul>
            <p><strong>Narxi:</strong> 1.755.000 So’m</p>
            <p><strong>O’zbekiston bo’ylab yetkazib berish xizmati bilan.</strong></p>
            <p><strong>Qo’shimcha va to’liq ma’lumot uchun:</strong></p>
            <p>☎️ 90-990 22 20</p>

        </div>

        <div id="about" class="content-section">
            <h2>About Us</h2>
           
            <p>🚘 Большой ассортимент авто аксессуаров</p>
            <p>🚘 Katta xajimdagi Avto aksessuarlar</p>
            <p>📝 Гарантия имеются</p>
            <p>⁉️ Qiziqtirgan maxsulot tagida komentariyani bosib savollarni berishingiz mumkin...</p>
            <p>⁉️ Можете задавать свои вопросы в комментариях...</p>
        </div>

        <div id="contact" class="content-section">
            <h2>Contact Us</h2>
            <p>Telegram: <a href="https://t.me/MARUFJONcom" target="_blank">@MARUFJONcom</a></p>
            <p>Instagram: <a href="https://t.me/auto_mrs777" target="_blank">@auto_mrs777</a></p>
            <p>Phone: +998 90 990 22 20</p>
        </div>
    </div>

  
    <script>
        function showContent(section) {
         
            const sections = document.querySelectorAll('.content-section');
            sections.forEach(section => section.classList.remove('active'));

            
            const activeSection = document.getElementById(section);
            activeSection.classList.add('active');
        }
    </script>

</body>
</html>
    

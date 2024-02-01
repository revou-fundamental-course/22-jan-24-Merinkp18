# 22-jan-24-Merinkp18
22-jan-24-Merinkp18 created by GitHub Classroom
<!DOCTYPE html>
<html lang="en">
<head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <img>
            <title>E Grocery</title>
        <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="logo"><a href="#">Moqups</a></div>
            <ul class="links">
                <li><a href="hero">Home</a></li>
                <li><a href="our-package">Our Package</a></li>
                <li><a href="call-us">Call Us</a></li>
            </ul>
            </div>
        </div>
        <div class="dropdown_menu">
            <li><a href="hero">Home</a></li>
            <li><a href="our-package">Our Package</a></li>
            <li><a href="call-us">Call Us</a></li>
        </div>
    </header>
    <header>
        <h1>Top Rated E-Groceries Shop in Indonesian</h1>
        <h3>Every Day with best ingredients</h3>
    </header>
    <main class="container">
        <div class="slides">
            <div class="slide">
                <img src="sayur-2.jpg" width="70%" height="70%" alt="">
            </div>
            <div class="slide">
                <img src="sayur-1.jpg" width="70%" height="70%" alt="">
            </div>
            <div class="slide">
                <img src="buah-1.jpg" width="70%" height="70%" alt="">
            </div>
            <div class="navigation">
                <a class="prev" onclick = "plusSlides(-1)">&#10094;</a>
                <a class="next" onclick = "plusSlides(-1)">&#10095;</a>
            </div>
        </div>
        </div>

        <script>
            var slideIndex = 1;
            showSlides(slideIndex);

            function plusSlides(n) {
                showSlides(slideIndeex += n);
            }

            function showSlides(n) {
                var i;
                var slides = document.getElementsByClassName("slide");
                if (n > slides.length)
                {
                    slideIndex = 1;
                }
                if (n < 1)
                {
                    slideIndex = slides.length
                }
                for (i = 0; i < slides.length; i++)
                {
                    slides[i].style.display = "none";
                }
                slides[slideIndex-1].style.display = "block";
            }
        </script>
        <div>
            <h4>"Setiap hari beli sayur buah yang fresh disini"</h4>
        </div>
        <p>
            <img src="th.jpg" alt="">   
        </p> 
        
        <div class="form">
            <form name="message-form" onsubmit="return validateForm()">
                <h3>Contact Us</h3>
                Your Name: <input placeholder="Fist and last your name" type="text" name="full-name" required />
                <br />
                
                Email Address:
                <input placeholder="example@email.com" type="text" name="email-address" required />
                <br />

                What are you intereted in?
                <select placeholder="Select option">
                    <option value="Fresh Vegetable">Fresh Vegetable</option>
                    <option value="Fresh Fruit">Fresh Fruit</option>
                    <option value="Instant Delivery">Instant Delivery</option>
                    <option value="Kitchen Ingredient">Kitchen Ingredient</option>
                    <option value="Kitchen Set">Kitchen Set</option>
                    <option value="Bunding Set">Bunding Set</option>
                </select> <br />
                
                <input type="submit" value="Submit" />
            </form>
        </div>
        <div class="deskripsi">
            <h2>Mengapa harus berbelanja di Store kami?</h2>
            <h4>Pilhan toko yang beragam</h4>
            <h4>Belanja kebutuhan online sesuai keinginanmu</h4>
            <h4>Pembayaran non-tunai yang aman</h4>
        </div>
        <div class="our-package">
            <h1>Our Package</h1>
            <h3>Fresh Vegetable</h3>
            <h3>Fresh Fruit</h3>
            <h3>Instant Delivery</h3>
            <h3>Kitchen Ingredient</h3>
            <h3>Kitchen Set</h3>
            <h3>Bunding Set</h3>
        </div>
    </main>
    <script src="js/script.js"></script>
</body>
</html>

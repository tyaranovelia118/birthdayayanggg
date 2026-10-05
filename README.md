
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Happy Birthday Ayang 💙</title>

    <!-- GOOGLE FONT -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;500;600;700;800&family=DM+Sans:wght@400;500;600;700&family=Pacifico&display=swap" rel="stylesheet">

    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: "DM Sans", sans-serif;
            background:
                linear-gradient(
                    180deg,
                    #bfe4ff 0%,
                    #eaf7ff 28%,
                    #ffffff 55%,
                    #e8f4ff 100%
                );
            color: #23415f;
            overflow-x: hidden;
        }

        /* =========================
           BACKGROUND
        ========================= */

        .background {
            position: fixed;
            inset: 0;
            overflow: hidden;
            pointer-events: none;
            z-index: -1;
        }

        .cloud {
            position: absolute;
            background: rgba(255,255,255,.8);
            border-radius: 100px;
            filter: blur(1px);
        }

        .cloud::before,
        .cloud::after {
            content: "";
            position: absolute;
            background: inherit;
            border-radius: 50%;
        }

        .cloud::before {
            width: 80px;
            height: 80px;
            left: 35px;
            bottom: 0;
        }

        .cloud::after {
            width: 60px;
            height: 60px;
            left: 90px;
            bottom: 0;
        }

        .cloud1 {
            width: 170px;
            height: 45px;
            top: 12%;
            left: -30px;
        }

        .cloud2 {
            width: 200px;
            height: 50px;
            top: 38%;
            right: -50px;
        }

        .cloud3 {
            width: 160px;
            height: 40px;
            bottom: 15%;
            left: 10%;
        }

        /* =========================
           FLOATING DECORATION
        ========================= */

        .floating {
            position: fixed;
            pointer-events: none;
            z-index: 0;
            animation: float 5s ease-in-out infinite;
        }

        .heart1 {
            left: 7%;
            top: 30%;
            font-size: 22px;
        }

        .heart2 {
            right: 8%;
            top: 20%;
            font-size: 27px;
            animation-delay: 1s;
        }

        .heart3 {
            right: 15%;
            bottom: 25%;
            font-size: 18px;
            animation-delay: 2s;
        }

        @keyframes float {

            0%,100% {
                transform: translateY(0) rotate(-5deg);
            }

            50% {
                transform: translateY(-20px) rotate(8deg);
            }
        }

        /* =========================
           NAVIGATION
        ========================= */

        nav {
            position: fixed;
            top: 15px;
            left: 50%;
            transform: translateX(-50%);
            width: calc(100% - 30px);
            max-width: 900px;
            padding: 12px 18px;
            border-radius: 50px;
            background: rgba(255,255,255,.75);
            backdrop-filter: blur(15px);
            box-shadow: 0 10px 30px rgba(47,110,165,.15);
            z-index: 100;
            display: flex;
            justify-content: center;
            gap: 22px;
        }

        nav a {
            color: #32658e;
            text-decoration: none;
            font-size: 12px;
            font-weight: 600;
        }

        nav a:hover {
            color: #e18fa9;
        }

        /* =========================
           HERO
        ========================= */

        .hero {
            min-height: 100vh;
            padding: 120px 20px 70px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .hero-content {
            max-width: 850px;
        }

        .small-label {
            color: #588ab2;
            font-size: 13px;
            font-weight: 700;
            letter-spacing: 4px;
            margin-bottom: 18px;
        }

        .hero h1 {
            font-family: "Baloo 2", sans-serif;
            font-size: clamp(50px, 13vw, 105px);
            line-height: .9;
            color: #2d78b5;
            font-weight: 800;
            text-shadow: 4px 5px 0 rgba(255,255,255,.9);
        }

        .hero .ayang {
            font-family: "Pacifico", cursive;
            font-size: clamp(70px, 18vw, 160px);
            color: #e294ad;
            line-height: 1;
            margin-top: 8px;
            text-shadow:
                3px 4px 0 white,
                0 10px 30px rgba(226,148,173,.25);
        }

        .hero-name {
            margin-top: 25px;
            font-size: 20px;
            font-weight: 700;
            letter-spacing: 3px;
            color: #315b7d;
        }

        .hero-text {
            max-width: 600px;
            margin: 18px auto;
            line-height: 1.8;
            color: #5b7690;
        }

        .from {
            font-family: "Pacifico", cursive;
            color: #4c83ad;
            font-size: 24px;
            margin-top: 18px;
        }

        .main-button {
            display: inline-block;
            margin-top: 30px;
            padding: 15px 28px;
            border-radius: 50px;
            background: linear-gradient(135deg, #4b96ce, #76b9e7);
            color: white;
            text-decoration: none;
            font-weight: 700;
            box-shadow: 0 12px 25px rgba(56,130,184,.25);
            transition: .3s;
        }

        .main-button:hover {
            transform: translateY(-5px);
        }

        /* =========================
           SECTION
        ========================= */

        section {
            padding: 90px 18px;
        }

        .container {
            width: min(100%, 950px);
            margin: auto;
        }

        .section-title {
            text-align: center;
            margin-bottom: 45px;
        }

        .section-title .emoji {
            font-size: 35px;
            margin-bottom: 10px;
        }

        .section-title h2 {
            font-family: "Baloo 2", sans-serif;
            font-size: clamp(35px, 7vw, 55px);
            color: #3279b1;
            line-height: 1;
        }

        .section-title p {
            max-width: 650px;
            margin: 15px auto 0;
            color: #69839a;
            line-height: 1.8;
        }

        /* =========================
           5 YEARS CARD
        ========================= */

        .years-card {
            background: white;
            border-radius: 35px;
            padding: 50px 25px;
            text-align: center;
            box-shadow: 0 20px 60px rgba(61,126,174,.15);
            border: 3px solid #e4f3ff;
            position: relative;
            overflow: hidden;
        }

        .years-card::before {
            content: "✦";
            position: absolute;
            top: 20px;
            left: 25px;
            font-size: 25px;
            color: #f0b3c5;
        }

        .years-card::after {
            content: "✦";
            position: absolute;
            bottom: 20px;
            right: 25px;
            font-size: 25px;
            color: #78b8e4;
        }

        .number-five {
            font-family: "Baloo 2", sans-serif;
            font-size: 150px;
            font-weight: 800;
            line-height: .8;
            color: #5aa1d2;
        }

        .five-title {
            font-family: "Baloo 2", sans-serif;
            font-size: 28px;
            color: #e197ae;
            font-weight: 700;
            margin-top: 20px;
        }

        .five-hearts {
            margin: 20px 0;
            letter-spacing: 8px;
            font-size: 22px;
        }

        .years-card p {
            max-width: 650px;
            margin: auto;
            line-height: 1.9;
            color: #668096;
        }

        /* =========================
           PHOTO MEMORIES
        ========================= */

        .photo-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .photo-card {
            background: white;
            padding: 12px 12px 22px;
            border-radius: 8px;
            box-shadow: 0 15px 35px rgba(46,106,153,.18);
            transition: .4s;
        }

        .photo-card:nth-child(1) {
            transform: rotate(-3deg);
        }

        .photo-card:nth-child(2) {
            transform: rotate(2deg);
        }

        .photo-card:nth-child(3) {
            transform: rotate(-2deg);
        }

        .photo-card:nth-child(4) {
            transform: rotate(2deg);
        }

        .photo-card:nth-child(5) {
            transform: rotate(-2deg);
        }

        .photo-card:nth-child(6) {
            transform: rotate(3deg);
        }

        .photo-card:hover {
            transform: translateY(-10px) rotate(0deg) scale(1.03);
            z-index: 5;
        }

        .photo-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 5px;
            display: block;
        }

        .photo-caption {
            text-align: center;
            padding-top: 15px;
            font-family: "Baloo 2", sans-serif;
            color: #487da5;
            font-size: 17px;
            font-weight: 600;
        }

        /* =========================
           MESSAGE
        ========================= */

        .message-card {
            background: white;
            border-radius: 30px;
            padding: 40px;
            box-shadow: 0 20px 60px rgba(56,116,158,.13);
            border-left: 7px solid #77b8df;
        }

        .message-card p {
            color: #5f768b;
            line-height: 2;
            margin-bottom: 25px;
            font-size: 15px;
        }

        .message-card p:last-child {
            margin-bottom: 0;
        }

        /* =========================
           BIRTHDAY PARTY
        ========================= */

        .party {
            background:
                linear-gradient(
                    135deg,
                    #d7efff,
                    #ffffff,
                    #fce8ef
                );
            border-radius: 40px;
            padding: 55px 25px;
            text-align: center;
            box-shadow: 0 20px 60px rgba(64,127,173,.15);
        }

        .balloons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 30px;
        }

        .balloon {
            width: 58px;
            height: 72px;
            border-radius: 50%;
            position: relative;
            box-shadow:
                inset -8px -10px 15px rgba(0,0,0,.12),
                inset 8px 7px 12px rgba(255,255,255,.55),
                0 10px 20px rgba(0,0,0,.12);
            animation: balloonFloat 3s ease-in-out infinite;
        }

        .balloon:nth-child(2) {
            animation-delay: .4s;
        }

        .balloon:nth-child(3) {
            animation-delay: .8s;
        }

        .balloon:nth-child(4) {
            animation-delay: 1.2s;
        }

        .balloon::after {
            content: "";
            position: absolute;
            width: 1px;
            height: 65px;
            background: #7393ac;
            left: 50%;
            top: 70px;
        }

        .b-blue {
            background: linear-gradient(135deg,#9bd5fa,#4388c0);
        }

        .b-pink {
            background: linear-gradient(135deg,#f8cbd8,#db8fa9);
        }

        .b-white {
            background: linear-gradient(135deg,#ffffff,#c9e0ef);
        }

        .b-purple {
            background: linear-gradient(135deg,#d9c8f4,#9b81ca);
        }

        @keyframes balloonFloat {
            0%,100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-15px);
            }
        }

        /* =========================
           CAKE
        ========================= */

        .cake {
            width: 260px;
            height: 190px;
            margin: 60px auto 35px;
            position: relative;
        }

        .cake-base {
            position: absolute;
            width: 230px;
            height: 105px;
            bottom: 0;
            left: 15px;
            background: linear-gradient(
                135deg,
                #ffffff,
                #d6edff
            );
            border-radius: 20px 20px 30px 30px;
            box-shadow: 0 20px 35px rgba(40,94,133,.2);
        }

        .cake-top {
            position: absolute;
            width: 230px;
            height: 65px;
            left: 15px;
            top: 25px;
            border-radius: 50%;
            background: #ffffff;
            box-shadow: 0 8px 20px rgba(53,108,147,.15);
            z-index: 2;
        }

        .cake-blue-line {
            position: absolute;
            width: 230px;
            height: 18px;
            left: 15px;
            top: 83px;
            background: #65a8d7;
            z-index: 3;
        }

        .cake-writing {
            position: absolute;
            z-index: 5;
            top: 44px;
            width: 100%;
            text-align: center;
            font-family: "Pacifico", cursive;
            font-size: 17px;
            color: #3478ad;
        }

        .candle {
            position: absolute;
            width: 10px;
            height: 48px;
            background: linear-gradient(
                90deg,
                #5f9fd0,
                #ffffff,
                #6aa8d5
            );
            top: -18px;
            z-index: 10;
            border-radius: 5px;
        }

        .candle1 {
            left: 95px;
        }

        .candle2 {
            left: 125px;
        }

        .flame {
            width: 16px;
            height: 22px;
            position: absolute;
            top: -22px;
            left: -3px;
            background: #ffd875;
            border-radius: 50% 50% 50% 0;
            transform: rotate(-45deg);
            box-shadow: 0 0 20px #ffd46d;
            animation: flame 1s ease-in-out infinite alternate;
        }

        @keyframes flame {
            from {
                transform: rotate(-45deg) scale(1);
            }
            to {
                transform: rotate(-45deg) scale(1.15);
            }
        }

        /* =========================
           WISH
        ========================= */

        .wish-card {
            background: linear-gradient(135deg,#5fa6d6,#8cc9ed);
            color: white;
            border-radius: 35px;
            padding: 45px 30px;
            box-shadow: 0 20px 60px rgba(49,121,172,.25);
        }

        .wish-card p {
            line-height: 2;
            margin-bottom: 25px;
            font-size: 15px;
        }

        .wish-card p:last-child {
            margin-bottom: 0;
        }

        /* =========================
           FINAL
        ========================= */

        .final {
            text-align: center;
            padding: 120px 20px;
        }

        .final h2 {
            font-family: "Baloo 2", sans-serif;
            font-size: clamp(45px,10vw,85px);
            line-height: 1;
            color: #367eb5;
        }

        .final p {
            max-width: 650px;
            margin: 25px auto;
            line-height: 1.9;
            color: #637c91;
        }

        .final-highlight {
            font-family: "Pacifico", cursive;
            font-size: clamp(28px,6vw,45px);
            color: #df94ab;
            margin-top: 30px;
        }

        .signature {
            font-family: "Pacifico", cursive;
            font-size: 38px;
            color: #4385b4;
            margin-top: 30px;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #3279ae;
            color: white;
            font-size: 11px;
            letter-spacing: 2px;
        }

        /* =========================
           REVEAL
        ========================= */

        .reveal {
            opacity: 0;
            transform: translateY(35px);
            transition: 1s ease;
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        /* =========================
           CONFETTI
        ========================= */

        .confetti {
            position: fixed;
            width: 9px;
            height: 15px;
            top: -20px;
            z-index: 999;
            pointer-events: none;
            animation: fall 3s linear forwards;
        }

        @keyframes fall {
            0% {
                transform: translateY(0) rotate(0);
            }

            100% {
                transform: translateY(110vh) rotate(720deg);
            }
        }

        /* =========================
           RESPONSIVE
        ========================= */

        @media (max-width: 700px) {

            nav {
                gap: 12px;
                padding: 11px 10px;
            }

            nav a {
                font-size: 9px;
            }

            .hero {
                padding-top: 120px;
            }

            .hero-name {
                font-size: 14px;
                letter-spacing: 2px;
            }

            .hero-text {
                font-size: 13px;
            }

            section {
                padding: 65px 15px;
            }

            .photo-grid {
                grid-template-columns: repeat(2,1fr);
                gap: 18px;
            }

            .photo-card img {
                height: 190px;
            }

            .message-card {
                padding: 25px 20px;
            }

            .message-card p,
            .wish-card p {
                font-size: 13px;
                line-height: 1.9;
            }

            .balloon {
                width: 45px;
                height: 60px;
            }

            .cake {
                transform: scale(.85);
            }
        }

        @media (max-width: 420px) {

            nav a:nth-child(n+5) {
                display: none;
            }

            .photo-grid {
                grid-template-columns: 1fr 1fr;
            }

            .photo-card img {
                height: 160px;
            }

            .number-five {
                font-size: 120px;
            }
        }

    </style>
</head>

<body>


<!-- =========================
     BACKGROUND
========================= -->

<div class="background">

    <div class="cloud cloud1"></div>
    <div class="cloud cloud2"></div>
    <div class="cloud cloud3"></div>

</div>

<div class="floating heart1">💙</div>
<div class="floating heart2">✨</div>
<div class="floating heart3">💗</div>


<!-- =========================
     NAVIGATION
========================= -->

<nav>

    <a href="#home">🏠 Home</a>
    <a href="#journey">💙 5 Tahun</a>
    <a href="#memories">📸 Foto</a>
    <a href="#message">💌 Pesan</a>
    <a href="#birthday">🎂 Birthday</a>
    <a href="#wish">✨ Doa</a>

</nav>


<!-- =========================
     HERO
========================= -->

<section class="hero" id="home">

    <div class="hero-content">

        <div class="small-label">
            ✨ A SPECIAL DAY FOR SOMEONE SPECIAL ✨
        </div>

        <h1>
            HAPPY
            <br>
            BIRTHDAY
        </h1>

        <div class="ayang">
            Ayang 💙
        </div>

        <div class="hero-name">
            MUH. TIO SUSANTO
        </div>

        <p class="hero-text">
            Untuk seseorang yang sudah menemani Tyara
            selama kurang lebih 5 tahun.
            Hari ini bukan cuma tentang bertambahnya usia,
            tapi juga tentang merayakan seseorang yang begitu berarti.
        </p>

        <div class="from">
            From Tyara, with lots of love 💙
        </div>

        <a href="#journey" class="main-button">
            💌 Buka Pesan dari Tyara
        </a>

    </div>

</section>


<!-- =========================
     5 YEARS
========================= -->

<section id="journey">

    <div class="container">

        <div class="section-title reveal">

            <div class="emoji">💙✨</div>

            <h2>
                Our 5 Year Journey
            </h2>

            <p>
                Lima tahun bukan hanya tentang waktu,
                tetapi tentang semua cerita yang sudah kita lewati.
            </p>

        </div>


        <div class="years-card reveal">

            <div class="number-five">
                5
            </div>

            <div class="five-title">
                TAHUN BERSAMA
            </div>

            <div class="five-hearts">
                💙 💙 💙 💙 💙
            </div>

            <p>
                5 tahun bukan waktu yang sebentar.
                Ada banyak cerita, tawa, momen bahagia,
                salah paham, perjuangan, dan kenangan yang
                sudah kita lewati bersama.
            </p>

            <p style="margin-top:20px;">
                Dan semoga masih banyak cerita yang
                menunggu kita di depan. ✨
            </p>

        </div>

    </div>

</section>


<!-- =========================
     MEMORIES
========================= -->

<section id="memories">

    <div class="container">

        <div class="section-title reveal">

            <div class="emoji">
                📸💙
            </div>

            <h2>
                Our Little Memories
            </h2>

            <p>
                Beberapa momen kecil yang menjadi bagian
                dari perjalanan panjang kita.
            </p>

        </div>


        <div class="photo-grid">


            <!-- FOTO 1 -->

            <div class="photo-card reveal">

                <img
                    src="images/foto1.jpg"
                    alt="Kenangan Tyara dan Ayang"
                >

                <div class="photo-caption">
                    Our little moment 💙
                </div>

            </div>


            <!-- FOTO 2 -->

            <div class="photo-card reveal">

                <img
                    src="images/foto2.jpg"
                    alt="Kenangan bersama"
                >

                <div class="photo-caption">
                    Favorite memory ✨
                </div>

            </div>


            <!-- FOTO 3 -->

            <div class="photo-card reveal">

                <img
                    src="images/foto3.jpg"
                    alt="Kenangan perjalanan"
                >

                <div class="photo-caption">
                    Another beautiful day 🤍
                </div>

            </div>


            <!-- FOTO 4 -->

            <div class="photo-card reveal">

                <img
                    src="images/foto4.jpg"
                    alt="Momen bersama"
                >

                <div class="photo-caption">
                    Just us 💙
                </div>

            </div>


            <!-- FOTO 5 -->

            <div class="photo-card reveal">

                <img
                    src="images/foto5.jpg"
                    alt="Kenangan 5 tahun"
                >

                <div class="photo-caption">
                    5 years of stories 🥹
                </div>

            </div>


            <!-- FOTO 6 -->

            <div class="photo-card reveal">

                <img
                    src="images/foto6.jpg"
                    alt="Foto favorit"
                >

                <div class="photo-caption">
                    One of my favorites 💗
                </div>

            </div>


        </div>

    </div>

</section>


<!-- =========================
     MESSAGE
========================= -->

<section id="message">

    <div class="container">

        <div class="section-title reveal">

            <div class="emoji">
                💌
            </div>

            <h2>
                A Little Message For You
            </h2>

        </div>


        <div class="message-card reveal">

            <p>
                Terima kasih sudah menemani Tyara dalam jangka
                waktu yang lumayan lama, yaitu kurang lebih 5 tahun.
            </p>

            <p>
                Lima tahun bukan waktu yang sebentar. Selama itu,
                pasti ada banyak cerita, tawa, kebahagiaan, bahkan
                mungkin ada juga salah paham, kecewa, dan masa-masa
                sulit yang sudah kita lewati bersama.
            </p>

            <p>
                Terima kasih karena selama ini Ayang sudah tetap ada,
                sudah meluangkan waktu, memberikan perhatian,
                mendengarkan cerita Tyara, dan menjadi bagian dari
                begitu banyak momen dalam hidup Tyara.
            </p>

            <p>
                Mungkin Tyara nggak selalu bisa mengungkapkan
                semuanya lewat kata-kata, tapi Tyara benar-benar
                menghargai setiap waktu, usaha, perhatian, kesabaran,
                dan kebersamaan yang sudah Ayang berikan selama
                5 tahun ini.
            </p>

        </div>

    </div>

</section>


<!-- =========================
     BIRTHDAY PARTY
========================= -->

<section id="birthday">

    <div class="container">

        <div class="party reveal">

            <div class="balloons">

                <div class="balloon b-blue"></div>
                <div class="balloon b-pink"></div>
                <div class="balloon b-white"></div>
                <div class="balloon b-purple"></div>

            </div>


            <div class="section-title">

                <div class="emoji">
                    🎂🎉
                </div>

                <h2>
                    Make A Wish, Ayang!
                </h2>

                <p>
                    Hari ini waktunya Ayang tersenyum,
                    meniup lilin, dan membuat banyak harapan baru.
                </p>

            </div>


            <!-- CAKE -->

            <div class="cake">

                <div class="candle candle1">
                    <div class="flame"></div>
                </div>

                <div class="candle candle2">
                    <div class="flame"></div>
                </div>

                <div class="cake-top"></div>

                <div class="cake-base"></div>

                <div class="cake-blue-line"></div>

                <div class="cake-writing">
                    Happy Birthday Ayang
                </div>

            </div>


            <button
                class="main-button"
                onclick="birthdaySurprise()"
                style="border:none; cursor:pointer;"
            >
                🎉 TIUP LILIN
            </button>

        </div>

    </div>

</section>


<!-- =========================
     WISH
========================= -->

<section id="wish">

    <div class="container">

        <div class="section-title reveal">

            <div class="emoji">
                ✨🤍
            </div>

            <h2>
                My Wish For You
            </h2>

        </div>


        <div class="wish-card reveal">

            <p>
                Di hari ulang tahun Ayang ini, Tyara cuma ingin
                mendoakan semoga Ayang selalu diberikan kesehatan,
                kebahagiaan, kesuksesan, rezeki yang luas, umur yang
                panjang, dan kekuatan untuk mencapai semua impian
                yang Ayang punya.
            </p>

            <p>
                Semoga setiap langkah Ayang selalu dimudahkan,
                setiap usaha Ayang diberikan hasil yang baik,
                dan semua hal yang sedang Ayang perjuangkan
                perlahan bisa menjadi kenyataan.
            </p>

            <p>
                Semoga di usia yang baru ini, hidup Ayang dipenuhi
                lebih banyak kebahagiaan, keberkahan, kesuksesan,
                dan hal-hal baik yang bahkan belum pernah Ayang bayangkan.
            </p>

        </div>

    </div>

</section>


<!-- =========================
     THANK YOU
========================= -->

<section>

    <div class="container">

        <div class="section-title reveal">

            <div class="emoji">
                💙
            </div>

            <h2>
                Thank You For 5 Years
            </h2>

        </div>


        <div class="message-card reveal">

            <p>
                Terima kasih sudah menjadi bagian dari perjalanan
                Tyara selama ini. Terima kasih sudah bertahan,
                sudah menemani, dan sudah menjadi seseorang yang
                begitu berarti dalam hidup Tyara.
            </p>

            <p>
                Terima kasih sudah hadir dan menemani Tyara sampai
                sejauh ini. Terima kasih untuk 5 tahun yang penuh cerita.
            </p>

            <p>
                Semoga setelah ini masih ada banyak tahun lagi yang
                bisa kita lewati bersama, menciptakan cerita baru,
                melewati banyak hal bersama, dan suatu hari nanti
                melihat kembali perjalanan ini dengan senyum.
            </p>

        </div>

    </div>

</section>


<!-- =========================
     FINAL
========================= -->

<section class="final">

    <div class="container reveal">

        <div style="font-size:40px;">
            🎈✨🎂✨🎈
        </div>

        <h2>
            SELAMAT ULANG TAHUN,
            <br>
            AYANG 💙
        </h2>

        <p>
            Semoga di usia yang baru ini, Ayang semakin bahagia,
            semakin sukses, semakin kuat, dan semakin dekat
            dengan semua impian Ayang.
        </p>

        <div class="final-highlight">
            5 years is only the beginning... 💙
        </div>

        <p>
            Terima kasih sudah menjadi bagian dari cerita
            Tyara selama 5 tahun ini.
            Semoga cerita kita belum selesai di sini.
        </p>

        <div class="signature">
            With lots and lots of love,
            <br>
            Tyara 💙
        </div>

    </div>

</section>


<footer>

    MADE WITH 💙 BY TYARA
    <br><br>
    FOR MUH. TIO SUSANTO

</footer>


<!-- =========================
     JAVASCRIPT
========================= -->

<script>


    /* =========================
       SCROLL REVEAL
    ========================= */

    const revealElements =
        document.querySelectorAll(".reveal");


    function revealOnScroll() {

        revealElements.forEach(element => {

            const top =
                element.getBoundingClientRect().top;

            const windowHeight =
                window.innerHeight;

            if (top < windowHeight - 80) {

                element.classList.add("active");

            }

        });

    }


    window.addEventListener(
        "scroll",
        revealOnScroll
    );


    revealOnScroll();



    /* =========================
       BIRTHDAY SURPRISE
    ========================= */

    function birthdaySurprise() {

        const flames =
            document.querySelectorAll(".flame");


        flames.forEach(flame => {

            flame.style.display = "none";

        });


        createConfetti();


        setTimeout(() => {

            alert(
                "🎉 YEAY! 🎉\n\n" +
                "Semoga semua doa dan harapan Ayang " +
                "di usia yang baru ini bisa terkabul. 💙✨\n\n" +
                "Happy Birthday, Ayang! 🎂"
            );

        }, 700);

    }



    /* =========================
       CONFETTI
    ========================= */

    function createConfetti() {

        const colors = [
            "#5aa8d8",
            "#8ccbf0",
            "#e49ab1",
            "#f4c9d5",
            "#ffffff",
            "#f2d48b"
        ];


        for (let i = 0; i < 100; i++) {

            const confetti =
                document.createElement("div");

            confetti.className =
                "confetti";


            confetti.style.left =
                Math.random() * 100 + "vw";


            confetti.style.background =
                colors[
                    Math.floor(
                        Math.random() *
                        colors.length
                    )
                ];


            confetti.style.animationDuration =
                (Math.random() * 2 + 2) + "s";


            confetti.style.transform =
                `rotate(${Math.random() * 360}deg)`;


            document.body.appendChild(confetti);


            setTimeout(() => {

                confetti.remove();

            }, 4000);

        }

    }

</script>

</body>
</html>

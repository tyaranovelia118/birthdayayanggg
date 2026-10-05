
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Happy Birthday Ayang 💙</title>

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
            color: #31506a;
            background: #f4fbff;
            overflow-x: hidden;
        }

        section {
            padding: 80px 20px;
        }

        .container {
            width: 100%;
            max-width: 950px;
            margin: auto;
        }

        /* =========================
           HERO
        ========================= */

        .hero {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
            overflow: hidden;

            background:
                radial-gradient(circle at 15% 20%,
                rgba(255,255,255,.9) 0 50px,
                transparent 51px),

                radial-gradient(circle at 85% 25%,
                rgba(255,255,255,.8) 0 70px,
                transparent 71px),

                linear-gradient(
                    145deg,
                    #bfe8ff,
                    #76c4f1,
                    #d9f3ff
                );
        }

        .hero-content {
            position: relative;
            z-index: 5;
            max-width: 750px;
        }

        .small-title {
            display: inline-block;
            padding: 8px 18px;
            border-radius: 30px;
            background: rgba(255,255,255,.85);
            color: #277db5;
            font-size: 12px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        .hero h1 {
            font-family: "Baloo 2", sans-serif;
            font-size: clamp(55px, 15vw, 115px);
            line-height: .8;
            color: white;
            margin-top: 30px;

            text-shadow:
                0 8px 0 rgba(39,125,181,.15),
                0 10px 30px rgba(39,125,181,.2);
        }

        .ayang {
            font-family: "Pacifico", cursive;
            font-size: clamp(50px, 13vw, 100px);
            color: white;
            margin-top: 10px;
            text-shadow: 0 5px 20px rgba(39,125,181,.25);
        }

        .hero h2 {
            color: white;
            font-size: clamp(18px, 4vw, 25px);
            letter-spacing: 4px;
            margin-top: 20px;
        }

        .hero p {
            color: white;
            line-height: 1.8;
            margin: 25px auto;
            max-width: 600px;
        }

        .btn {
            display: inline-block;
            padding: 14px 25px;
            border-radius: 50px;
            background: white;
            color: #277db5;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 10px 25px rgba(39,125,181,.2);
            transition: .3s;
            border: none;
            cursor: pointer;
            font-size: 15px;
        }

        .btn:hover {
            transform: translateY(-4px);
        }

        .btn-blue {
            background: #277db5;
            color: white;
        }

        /* FLOATING EMOJI */

        .floating {
            position: absolute;
            font-size: 35px;
            animation: floating 5s infinite ease-in-out;
        }

        .heart1 {
            top: 20%;
            left: 8%;
        }

        .heart2 {
            top: 35%;
            right: 8%;
            animation-delay: 1s;
        }

        .heart3 {
            bottom: 15%;
            left: 15%;
            animation-delay: 2s;
        }

        .heart4 {
            bottom: 20%;
            right: 15%;
            animation-delay: .5s;
        }

        @keyframes floating {

            0%,100% {
                transform: translateY(0) rotate(-5deg);
            }

            50% {
                transform: translateY(-20px) rotate(5deg);
            }

        }

        /* =========================
           TITLE
        ========================= */

        .section-title {
            text-align: center;
            margin-bottom: 40px;
        }

        .section-title small {
            color: #63aeda;
            font-weight: bold;
            letter-spacing: 2px;
        }

        .section-title h2 {
            font-family: "Baloo 2", sans-serif;
            color: #277db5;
            font-size: clamp(40px, 9vw, 65px);
            line-height: 1;
            margin: 10px 0;
        }

        .section-title p {
            max-width: 650px;
            margin: auto;
            line-height: 1.8;
        }

        /* =========================
           5 YEARS
        ========================= */

        .years {
            background: white;
        }

        .year-card {
            max-width: 800px;
            margin: auto;
            padding: 40px 25px;
            text-align: center;
            border-radius: 35px;

            background: linear-gradient(
                135deg,
                #effaff,
                white
            );

            box-shadow:
                0 15px 45px rgba(55,145,198,.1);
        }

        .number-five {
            font-family: "Baloo 2", sans-serif;
            font-size: 150px;
            line-height: .7;
            color: #65b9ef;
            font-weight: 800;
        }

        .year-card h3 {
            color: #4a9dcc;
            font-size: 22px;
            margin-top: 25px;
        }

        .five-hearts {
            font-size: 25px;
            margin: 20px 0;
            letter-spacing: 5px;
        }

        .year-card p {
            line-height: 2;
        }

        /* =========================
           MEMORY
        ========================= */

        .memories {
            background: linear-gradient(
                #ffffff,
                #eef9ff
            );
        }

        .memory-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .memory-card {
            background: white;
            padding: 30px 20px;
            border-radius: 28px;
            text-align: center;

            box-shadow:
                0 12px 30px rgba(50,100,130,.12);

            transition: .3s;
        }

        .memory-card:hover {
            transform: translateY(-8px);
        }

        .memory-icon {
            width: 85px;
            height: 85px;
            margin: auto auto 20px;

            display: flex;
            justify-content: center;
            align-items: center;

            border-radius: 50%;
            background: #eaf7ff;

            font-size: 40px;
        }

        .memory-card h3 {
            font-family: "Baloo 2", sans-serif;
            font-size: 25px;
            color: #4b9dce;
            margin-bottom: 10px;
        }

        .memory-card p {
            line-height: 1.8;
            font-size: 14px;
        }

        /* =========================
           MESSAGE
        ========================= */

        .message {
            background: #f8fcff;
        }

        .message-box {
            max-width: 820px;
            margin: auto;
            background: white;
            padding: 40px 30px;
            border-radius: 35px;

            box-shadow:
                0 15px 50px rgba(40,120,170,.1);
        }

        .message-box p {
            line-height: 2;
            margin-bottom: 18px;
        }

        .signature {
            font-family: "Pacifico", cursive;
            color: #5ca8d8;
            font-size: 25px;
            text-align: right;
            margin-top: 30px;
        }

        /* =========================
           PARTY
        ========================= */

        .party {
            background: linear-gradient(
                145deg,
                #7bc7f4,
                #b9e5ff
            );

            text-align: center;
        }

        .party .section-title h2,
        .party .section-title p {
            color: white;
        }

        .party-box {
            max-width: 700px;
            margin: auto;
            padding: 45px 20px;

            background: rgba(255,255,255,.88);

            border-radius: 40px;

            box-shadow:
                0 20px 50px rgba(39,125,181,.18);
        }

        /* CAKE */

        .cake {
            width: 210px;
            height: 160px;
            position: relative;
            margin: 30px auto;
        }

        .cake-body {
            position: absolute;
            width: 190px;
            height: 85px;
            left: 10px;
            bottom: 0;

            background: linear-gradient(
                #f8c5d4,
                #ef9eb9
            );

            border-radius: 15px 15px 25px 25px;

            box-shadow:
                0 8px 0 #df7e9e;
        }

        .cake-top {
            position: absolute;
            width: 155px;
            height: 45px;
            left: 28px;
            top: 40px;

            background: #fff0f5;
            border-radius: 50%;
        }

        .candle {
            position: absolute;
            width: 13px;
            height: 45px;
            bottom: 85px;

            background: repeating-linear-gradient(
                45deg,
                white 0 6px,
                #74bced 6px 12px
            );

            border-radius: 5px;
            z-index: 3;
        }

        .candle1 {
            left: 60px;
        }

        .candle2 {
            left: 99px;
        }

        .candle3 {
            left: 138px;
        }

        .flame {
            width: 16px;
            height: 22px;
            position: absolute;
            top: -20px;
            left: -2px;

            background: #ffd45c;
            border-radius: 50%;

            box-shadow:
                0 0 18px #ffd45c;

            animation: flame .7s infinite alternate;
        }

        @keyframes flame {

            from {
                transform: scale(.8);
            }

            to {
                transform: scale(1);
            }

        }

        .blown .flame {
            display: none;
        }

        .party-box h3 {
            font-family: "Baloo 2", sans-serif;
            color: #4b9dce;
            font-size: 30px;
        }

        .party-box p {
            line-height: 1.8;
            margin: 10px auto 25px;
        }

        /* =========================
           WISH
        ========================= */

        .wishes {
            background: white;
        }

        .wish-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 18px;
        }

        .wish {
            padding: 25px;
            border-radius: 25px;

            background: #f2faff;
            border: 1px solid #d8effd;

            line-height: 1.8;
        }

        .wish strong {
            display: block;
            color: #4b9dce;
            margin-bottom: 8px;
            font-size: 17px;
        }

        /* =========================
           FINAL
        ========================= */

        .final {
            min-height: 85vh;

            display: flex;
            justify-content: center;
            align-items: center;

            text-align: center;

            background:
                linear-gradient(
                    160deg,
                    #5baee1,
                    #a9defd 60%,
                    #f4c7d5
                );

            color: white;
        }

        .final h2 {
            font-family: "Baloo 2", sans-serif;
            font-size: clamp(50px, 12vw, 90px);
            line-height: .9;
        }

        .final .love {
            font-family: "Pacifico", cursive;
            font-size: clamp(25px, 6vw, 40px);
            margin: 25px 0;
        }

        .final p {
            line-height: 1.8;
        }

        footer {
            background: #367fae;
            color: #eaf7ff;
            text-align: center;
            padding: 25px 15px;
            font-size: 13px;
        }

        /* =========================
           CONFETTI
        ========================= */

        .confetti {
            position: fixed;
            top: -20px;

            width: 8px;
            height: 14px;

            z-index: 999;

            animation:
                fall 3.5s linear forwards;
        }

        @keyframes fall {

            to {
                transform:
                    translateY(110vh)
                    rotate(720deg);

                opacity: 0;
            }

        }

        /* =========================
           MOBILE
        ========================= */

        @media(max-width:700px) {

            section {
                padding: 65px 15px;
            }

            .memory-grid {
                grid-template-columns: 1fr;
            }

            .wish-grid {
                grid-template-columns: 1fr;
            }

            .number-five {
                font-size: 120px;
            }

            .message-box {
                padding: 30px 20px;
            }

            .floating {
                font-size: 25px;
            }

        }

    </style>
</head>


<body>


<!-- =========================
     HALAMAN PEMBUKA
========================= -->

<section class="hero">

    <span class="floating heart1">💙</span>
    <span class="floating heart2">🎈</span>
    <span class="floating heart3">✨</span>
    <span class="floating heart4">🤍</span>

    <div class="hero-content">

        <div class="small-title">
            A SPECIAL DAY FOR SOMEONE SPECIAL ✨
        </div>

        <h1>
            HAPPY<br>
            BIRTHDAY
        </h1>

        <div class="ayang">
            Ayang 💙
        </div>

        <h2>
            MUH. TIO SUSANTO
        </h2>

        <p>
            Hari ini adalah hari spesial untuk seseorang
            yang sudah menjadi bagian penting dalam perjalanan
            hidup Tyara.
            Selamat ulang tahun, Ayang! 💙
        </p>

        <a href="#message" class="btn">
            💌 Buka Pesan dari Tyara
        </a>

    </div>

</section>



<!-- =========================
     5 TAHUN BERSAMA
========================= -->

<section class="years">

    <div class="container">

        <div class="section-title">

            <small>
                OUR STORY
            </small>

            <h2>
                5 Years of Us 💙
            </h2>

            <p>
                Lima tahun bukan waktu yang sebentar.
                Ada banyak cerita, tawa, perjuangan,
                kesabaran, dan kenangan yang sudah kita
                lewati bersama.
            </p>

        </div>


        <div class="year-card">

            <div class="number-five">
                5
            </div>

            <h3>
                TAHUN BERSAMA
            </h3>

            <div class="five-hearts">
                💙 💙 💙 💙 💙
            </div>

            <p>
                Dari hari-hari sederhana sampai momen
                yang tidak akan pernah terlupakan,
                terima kasih karena sudah menjadi bagian
                dari perjalanan Tyara.

                <br><br>

                Lima tahun penuh cerita.
                Lima tahun penuh pembelajaran.
                Lima tahun dengan banyak sekali
                kenangan yang akan selalu punya tempat
                spesial di hati.

                <br><br>

                Semoga cerita kita terus bertambah,
                satu halaman demi satu halaman. 🥹
            </p>

        </div>

    </div>

</section>



<!-- =========================
     CERITA
========================= -->

<section class="memories">

    <div class="container">

        <div class="section-title">

            <small>
                OUR LITTLE MEMORIES
            </small>

            <h2>
                Potongan Cerita Kita ✨
            </h2>

            <p>
                Tidak semua kenangan harus disimpan
                dalam sebuah foto.
                Ada beberapa cerita yang cukup
                disimpan di hati.
            </p>

        </div>


        <div class="memory-grid">


            <div class="memory-card">

                <div class="memory-icon">
                    🥰
                </div>

                <h3>
                    Awal Cerita
                </h3>

                <p>
                    Dari awal mengenal sampai akhirnya
                    kita berjalan bersama.

                    Semua yang terjadi menjadi bagian
                    dari cerita yang tidak akan pernah
                    Tyara lupakan.
                </p>

            </div>



            <div class="memory-card">

                <div class="memory-icon">
                    😂
                </div>

                <h3>
                    Tawa Kita
                </h3>

                <p>
                    Ada banyak momen sederhana yang
                    mungkin terlihat biasa.

                    Tetapi justru hal-hal kecil itulah
                    yang sering menjadi kenangan
                    paling menyenangkan.
                </p>

            </div>



            <div class="memory-card">

                <div class="memory-icon">
                    🤍
                </div>

                <h3>
                    Perjalanan Kita
                </h3>

                <p>
                    Lima tahun mengajarkan kita tentang
                    sabar, memahami, saling mendukung,
                    dan tetap memilih satu sama lain.
                </p>

            </div>


        </div>

    </div>

</section>



<!-- =========================
     PESAN TYARA
========================= -->

<section class="message" id="message">

    <div class="container">

        <div class="section-title">

            <small>
                FROM TYARA
            </small>

            <h2>
                A Little Message 💌
            </h2>

        </div>


        <div class="message-box">

            <p>
                Happy birthday, Ayang. 💙
            </p>

            <p>
                Hari ini Tyara cuma ingin bilang terima kasih
                karena selama lima tahun ini kamu sudah hadir
                dan menjadi salah satu bagian paling berarti
                dalam perjalanan hidup Tyara.
            </p>

            <p>
                Terima kasih untuk semua waktu yang sudah kita
                lewati bersama. Terima kasih untuk tawa,
                perhatian, kesabaran, cerita-cerita kecil,
                dan kenangan yang mungkin terlihat sederhana
                tetapi selalu punya tempat spesial di hati Tyara.
            </p>

            <p>
                Kita mungkin tidak selalu punya hari yang sempurna.
                Ada salah paham, ada perbedaan, ada hari ketika
                semuanya terasa berat.
            </p>

            <p>
                Tapi dari semua itu, Tyara belajar bahwa sebuah
                hubungan bukan tentang selalu sempurna.
                Hubungan adalah tentang dua orang yang terus
                belajar memahami, saling menguatkan, dan tetap
                memilih untuk berjalan bersama.
            </p>

            <p>
                Terima kasih sudah menjadi seseorang yang menemani
                perjalanan Tyara sampai sejauh ini.
                Lima tahun bersama bukan hanya tentang lamanya
                waktu, tetapi tentang banyaknya cerita yang sudah
                kita lewati.
            </p>

            <p>
                Semoga di umur yang baru ini kamu semakin bahagia,
                semakin kuat, semakin sukses, dan semua hal baik
                yang kamu impikan perlahan menemukan jalannya.
            </p>

            <p>
                Jangan lupa untuk selalu menjaga diri.
                Jangan terlalu keras kepada diri sendiri.
                Dan jangan pernah lupa bahwa kamu layak mendapatkan
                hal-hal baik dalam hidup.
            </p>

            <p>
                Sekali lagi, selamat ulang tahun, Ayang.
                Semoga hari ini menjadi salah satu hari yang
                paling bahagia untukmu. 💙
            </p>


            <div class="signature">
                Love, Tyara 💙
            </div>

        </div>

    </div>

</section>



<!-- =========================
     KUE ULANG TAHUN
========================= -->

<section class="party">

    <div class="container">

        <div class="section-title">

            <small style="color:white;">
                BIRTHDAY PARTY
            </small>

            <h2>
                Make A Wish! 🎂
            </h2>

            <p>
                Karena ulang tahun Ayang harus dirayakan
                dengan senyum, doa, dan sedikit kejutan. 🎉
            </p>

        </div>


        <div class="party-box">

            <div class="cake" id="cake">

                <div class="candle candle1">
                    <div class="flame"></div>
                </div>

                <div class="candle candle2">
                    <div class="flame"></div>
                </div>

                <div class="candle candle3">
                    <div class="flame"></div>
                </div>

                <div class="cake-top"></div>

                <div class="cake-body"></div>

            </div>


            <h3>
                Happy Birthday, Ayang! 💙
            </h3>

            <p>
                Pejamkan mata,
                buat satu permohonan,
                lalu tiup lilinnya! ✨
            </p>

            <button
                class="btn btn-blue"
                id="blowButton"
                onclick="blowCandles()">

                🎉 TIUP LILIN

            </button>

        </div>

    </div>

</section>



<!-- =========================
     DOA
========================= -->

<section class="wishes">

    <div class="container">

        <div class="section-title">

            <small>
                MY WISH FOR YOU
            </small>

            <h2>
                Doa Tyara untuk Ayang ✨
            </h2>

        </div>


        <div class="wish-grid">


            <div class="wish">

                <strong>
                    💙 Kebahagiaan
                </strong>

                Semoga kamu selalu dikelilingi
                orang-orang yang tulus menyayangi,
                mendukung, dan menghargai kamu.

            </div>



            <div class="wish">

                <strong>
                    🌟 Kesuksesan
                </strong>

                Semoga setiap usaha, cita-cita,
                dan langkahmu dipermudah dan
                membawa hasil terbaik.

            </div>



            <div class="wish">

                <strong>
                    🌿 Kesehatan
                </strong>

                Semoga kamu selalu diberikan
                kesehatan, kekuatan, umur panjang,
                dan tubuh yang selalu kuat.

            </div>



            <div class="wish">

                <strong>
                    🙏 Ketenangan
                </strong>

                Semoga hatimu selalu diberikan
                ketenangan ketika menghadapi
                hari-hari yang tidak mudah.

            </div>



            <div class="wish">

                <strong>
                    ✨ Impian
                </strong>

                Semoga satu per satu impianmu
                bisa terwujud pada waktu yang
                paling tepat.

            </div>



            <div class="wish">

                <strong>
                    🤍 Kita
                </strong>

                Semoga perjalanan lima tahun ini
                menjadi awal dari lebih banyak
                cerita indah yang akan kita jalani
                bersama.

            </div>


        </div>

    </div>

</section>



<!-- =========================
     PENUTUP
========================= -->

<section class="final">

    <div class="container">

        <div style="font-size:50px;margin-bottom:25px;">
            🎈 💙 🎂 💙 🎈
        </div>

        <h2>
            SELAMAT<br>
            ULANG TAHUN,<br>
            AYANG! 💙
        </h2>

        <div class="love">
            5 years is only the beginning...
        </div>

        <p>
            Semoga senyum kamu hari ini menjadi awal
            dari banyak kebahagiaan di hari-hari berikutnya.
        </p>

        <p>
            Terima kasih sudah menjadi bagian dari cerita Tyara.
        </p>

        <p style="
            margin-top:25px;
            font-family:'Pacifico';
            font-size:25px;
        ">
            With lots and lots of love,
            Tyara 🤍
        </p>

    </div>

</section>



<footer>

    Made with 💙, memories, prayers & lots of love — Tyara

</footer>



<script>

function blowCandles() {

    const cake =
        document.getElementById("cake");

    const button =
        document.getElementById("blowButton");

    cake.classList.add("blown");

    button.innerHTML =
        "💙 WISH GRANTED!";

    /* CONFETTI */

    for(let i = 0; i < 60; i++) {

        const confetti =
            document.createElement("span");

        confetti.className =
            "confetti";

        confetti.style.left =
            Math.random() * 100 + "vw";

        confetti.style.background =
            [
                "#65b9ef",
                "#f5b8ca",
                "#e8c878",
                "#ffffff",
                "#8fd1f5"
            ][
                Math.floor(Math.random() * 5)
            ];

        confetti.style.animationDelay =
            Math.random() * .8 + "s";

        document.body.appendChild(confetti);

        setTimeout(() => {

            confetti.remove();

        }, 4500);

    }

}

</script>


</body>
</html>

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>مفاجأة لي حنونتي ❣️🌎</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #160b12, #4a1025, #12070d);
      color: white;
      text-align: center;
    }

    .login {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    .box {
      width: 100%;
      max-width: 450px;
      padding: 35px 25px;
      border-radius: 30px;
      background: rgba(255,255,255,0.09);
      box-shadow: 0 0 35px rgba(255,70,130,0.3);
    }

    .heart {
      font-size: 65px;
      animation: beat 1s infinite;
    }

    @keyframes beat {
      50% {
        transform: scale(1.12);
      }
    }

    h1 {
      color: #ff9fbd;
      font-size: 30px;
    }

    input {
      width: 100%;
      padding: 16px;
      border: none;
      border-radius: 18px;
      margin: 15px 0;
      text-align: center;
      font-size: 18px;
      outline: none;
    }

    button {
      border: none;
      border-radius: 18px;
      padding: 15px 30px;
      background: #ff4f91;
      color: white;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
    }

    .error {
      color: #ff8f8f;
      margin-top: 15px;
      display: none;
    }

    #site {
      display: none;
      padding: 25px 15px 50px;
    }

    .message {
      max-width: 700px;
      margin: 25px auto;
      padding: 25px;
      border-radius: 25px;
      background: rgba(255,255,255,0.08);
      line-height: 2.1;
      font-size: 18px;
    }

    .counter {
      max-width: 650px;
      margin: 25px auto;
      padding: 25px;
      border-radius: 25px;
      background: rgba(255,255,255,0.08);
    }

    .time {
      color: #ff9fc0;
      font-size: 22px;
      font-weight: bold;
      line-height: 2;
    }

    .music {
      max-width: 600px;
      margin: 30px auto;
    }

    audio {
      width: 100%;
      max-width: 500px;
    }

    .gallery {
      max-width: 900px;
      margin: 25px auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 15px;
    }

    .gallery img {
      width: 100%;
      border-radius: 20px;
      display: block;
      box-shadow: 0 5px 20px rgba(0,0,0,0.4);
    }

    .footer {
      margin-top: 35px;
      color: #ffabc6;
    }
  </style>
</head>

<body>

  <!-- شاشة الباسورد -->
  <div class="login" id="login">

    <div class="box">

      <div class="heart">❣️🌎</div>

      <h1>مفاجأة لي حنونتي ❣️🌎</h1>

      <p>فيه حاجة صغيرة مستنياكي هنا ❤️</p>

      <input
        type="password"
        id="password"
        placeholder="اكتبي الباسورد"
      >

      <button onclick="openSite()">
        افتحي يا حنونتي ❤️
      </button>

      <div class="error" id="error">
        الباسورد غلط 😭❤️
      </div>

    </div>

  </div>


  <!-- المفاجأة -->
  <div id="site">

    <div class="heart">❤️</div>

    <h1>حنونتي نور عيني وحياتي كلها ❣️🌎</h1>


    <!-- الرسالة -->
    <div class="message">

      حنونتي نور عيني وحياتي كلها❣️🌎
      <br><br>

      الي اول ما دخلت حياتي غيرتهااا للاحسن 😍
      <br>

      وحسيت معاكي يعني اي حب وغيره و خناق وزعل وضحك وهزار
      وكل حاجة حلوه💓
      <br><br>

      دي اقل حاجة ممكن اعملهالك انتي تستاهلي اكتر من كدا ب كتير 👑🤍
      كفاية انك معاياا وجنبي وسندي في الدنيا لما ببقا مقفول
      ومش ببقا دايق حد
      <br><br>

      مفيش غيرك بروح ليها عشان مفيش غيرك الي بحس اني مرتاح معاه
      في الكلام 🗣️
      مفيش غيرك في عنيه اصلا
      بحبك يا حنونتي ❣️😉
      <br><br>

      مهما اتخانقنا ومهما حصل حبي ليكي مش هيقل 😍
      الصور دي ذكريات معاكي عمري ما انساها
      عشتها معاكي يا روح قلبي ولسه مكملين إن شاء الله 🙏😍
      <br><br>

      وإن شاء الله نحقق كل الي احنا نفسنا فيه واحنا مع بعض 🫂♥️
      بحبك يا بنوتي ربنا يخليكي ليا وميحرمنيش منك ابدااا❣️💍💟

    </div>


    <!-- العداد -->
    <div class="counter">

      <h2>⏱️ عداد حكايتنا ❤️</h2>

      <div class="time" id="counter">
        جاري الحساب...
      </div>

      <p>
        من يوم 16 / 3 / 2026 الساعة 11:11 مساءً ❤️
      </p>

    </div>


    <!-- الأغنية -->
    <div class="music">

      <h2>🎵 أغنيتنا ❤️</h2>

      <audio id="music" controls loop>
        <source src="song.mp3" type="audio/mpeg">
      </audio>

    </div>


    <!-- الصور -->
    <h2>📸 ذكرياتنا ❤️</h2>

    <div class="gallery" id="gallery">
      جاري تحميل الصور...
    </div>


    <div class="footer">
      حنونتي ❣️🌎
      <br>
      ولسه أجمل الذكريات جاية ❤️
    </div>

  </div>


  <script>

    /* فتح المفاجأة وتشغيل الأغنية */
    function openSite() {

      const password =
        document.getElementById("password").value;

      if (password === "1732026") {

        document.getElementById("login").style.display = "none";

        document.getElementById("site").style.display = "block";

        /*
          تشغيل الأغنية بمجرد الضغط على زر الدخول.
          لأن الضغط على الزر يعتبر تفاعل من المستخدم.
        */
        const music =
          document.getElementById("music");

        music.play().catch(function() {
          console.log("المتصفح منع التشغيل التلقائي.");
        });

        loadImages();

      } else {

        document.getElementById("error").style.display = "block";

      }
    }


    /* العداد */

    const startDate =
      new Date("2026-03-16T23:11:00");

    function updateCounter() {

      const now = new Date();

      let difference = now - startDate;

      if (difference < 0) {

        document.getElementById("counter").innerHTML =
          "العداد لسه هيبدأ ❤️";

        return;
      }

      const totalSeconds =
        Math.floor(difference / 1000);

      const days =
        Math.floor(totalSeconds / 86400);

      const hours =
        Math.floor((totalSeconds % 86400) / 3600);

      const minutes =
        Math.floor((totalSeconds % 3600) / 60);

      const seconds =
        totalSeconds % 60;

      document.getElementById("counter").innerHTML =
        days + " يوم ❤️<br>" +
        hours + " ساعة ⏰<br>" +
        minutes + " دقيقة 💕<br>" +
        seconds + " ثانية";

    }

    setInterval(updateCounter, 1000);

    updateCounter();


    /* تحميل الصور الموجودة في المستودع */

    async function loadImages() {

      const gallery =
        document.getElementById("gallery");

      try {

        const response = await fetch(
          "https://api.github.com/repos/body96455-commits/body96455-commits.github.io/contents/"
        );

        const files = await response.json();

        gallery.innerHTML = "";

        const images =
          files.filter(function(file) {

            return /\.(jpg|jpeg|png|webp|gif)$/i
              .test(file.name);

          });

        images.forEach(function(file) {

          const img =
            document.createElement("img");

          img.src = file.download_url;

          img.alt = "ذكرى ❤️";

          gallery.appendChild(img);

        });

      } catch (error) {

        gallery.innerHTML =
          "<p>حصلت مشكلة في تحميل الصور ❤️</p>";

      }

    }

  </script>

</body>
</html>

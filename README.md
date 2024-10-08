<head>
    <link rel="stylesheet" href="styles.css"> <!-- Dosya adı ve yolu doğru olmalı -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Avukat Nural Kılıç</title>
    <style>
        :root {
            --font-size-large: 14px;
            --font-size-medium: 12px;
            --font-size-small: 10px;
            --font-size-xsmall: 8px;
            --font-size-xxsmall: 7px;
        }
        body {
            margin: 0;
            font-family: 'Garamond', 'Times New Roman', serif; /* Garamond benzeri fontları kullan */
            background-color: #333; /* Füme zemin */
            color: #000080; /* Metin rengi */
            font-size: var(--font-size-small); /* Varsayılan yazı boyutu */
        }


        /* İnce bar ve başlık */
        .top-bar {
            background-color: #000;
            padding: 10px;
            color: #C3B7EA;
            font-size: var(--font-size-medium);
            text-align: left;
        }

        /* Header için */
        .header {
            text-align: center;
            margin-top: 20px;
        }

        .header img {
            width: 100%;
            height: auto; /* Görselin oranlarını korur */
            max-height: 300px; /* İsteğe bağlı, yüksekliği sınırlamak için */
        }

        /* HAKKIMIZDA bölümü */
        .about {
            background-color: #C3B7EA;
            padding: 50px;
            display: flex;
            justify-content: space-between;
        }

        .about img {
            width: 45%;
            border-radius: 10px;
        }

        .about-text {

            color: #000080;
            font-size: var(--font-size-medium);
            width: 45%;
        }

        /* İHTİSAS ALANLARIMIZ bölümü */
.specialties {
    background-color: #C3B7EA;
    padding: 50px;
    text-align: center;
}

.specialties h2 {
    color: #000080;
    font-size: 12px; /* Başlığı 12px yapar */
    text-transform: uppercase; /* Başlığı büyük harf yapar */
}

.specialties-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.specialty-item {
    text-align: center;
}

.specialty-item img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-bottom: 10px;
}


        /* DİĞER ÇALIŞMA ALANLARIMIZ bölümü */
        .gallery {
            background-color: #C3B7EA;
            padding: 50px;
            text-align: center;
        }

        .gallery h2 {
            color: #000080;
            font-size: var(--font-size-large);
        }

        .gallery-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
        }

        .gallery-container img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
        }

        /* MÜRÂCAAT Bölümü */
        .application {
            background-color: #C3B7EA;
            padding: 75px;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }

        .contact-info {
            width: 45%;
            background-color: #C3B7EA;
            padding: 20px;
            border-radius: 10px;
            margin-right: 20px;
        }

        .contact-info h2 {
            color: #000080;
            font-size: var(--font-size-large);
        }

        .contact-info p {
            font-size: var(--font-size-small);
            margin: 10px 0;
        }

        .contact-info .contact-details {
            margin: 20px 0;
        }

        .contact-info .contact-details span {
            display: block;
            margin-bottom: 10px;
        }

        .contact-info .contact-details span strong {
            color: #000080;
        }

        .contact-info .calendar {
            background-color: #C3B7EA;
            padding: 10px;
            border-radius: 5px;
        }

        .contact-info .calendar h3 {
            color: #000080;
            font-size: var(--font-size-medium);
        }

        .contact-info .calendar p {
            font-size: var(--font-size-medium);
            margin: 5px 0;
        }

        /* Randevu talebi formu */
        .appointment-form {
            display: none; /* Form başlangıçta gizli */
            background-color: #C3B7EA;
            padding: 20px;
            border-radius: 10px;
            width: 100%;
            max-width: 600px;
            margin-top: 20px;
        }

        .appointment-form h2 {
            color: #000080;
            font-size: var(--font-size-large);
        }

        .appointment-form input, .appointment-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #000080;
        }

        .appointment-form button {
            width: 100%;
            padding: 10px;
            background-color: #000080;
            color: #C3B7EA;
            border: none;
            border-radius: 5px;
            font-size: var(--font-size-small);
        }

        .show-form-button {
            padding: 10px;
            background-color: #000080;
            color: #C3B7EA;
            border: none;
            border-radius: 5px;
            font-size: var(--font-size-small);
            cursor: pointer;
        }

        /* Footer */
        .footer {
            background-color: #000;
            color: #C3B7EA;
            padding: 20px;
            text-align: center;
        }

        .footer .social-media a {
            color: #C3B7EA;
            margin: 0 10px;
            text-decoration: none;
        }

        .footer .contact-details p {
            margin: 5px 0;
        }

        .footer .copyright {
            font-size: var(--font-size-xxsmall);
        }
    </style>
</head>
<body>

    <!-- İnce bar ve başlık -->
    <div class="top-bar">
        AVUKAT NURAL KILIÇ
    </div>

    <!-- Header -->
    <header>
    <img src="images/wbanner.png" alt="Header Görseli">
</header>


    <!-- Hakkımızda Bölümü -->
    <section class="about">
        <img src="images/hakkımızda.jpg" alt="Hakkımızda Görseli">
        <div class="about-text">
            <h2>Hakkımızda</h2>
            <p>Avukat Nural Kılıç ilk ve orta öğrenimini Adana'da görmüş, İstanbul Üniversitesi Hukuk Fakültesi'nden mezun olmuştur. Yasal stajını tamamlayıp avukatlık ruhsatnamesini alarak kıdemli meslektaşlarının hukuk bürolarında tecrübe kazandıktan sonra vekillik mesleğini kendi namına yapmaya başlamıştır. Mesleğinin ilk yıllarından itibaren hak odaklı çalışmalarda da yer almaya çabalayan Kılıç, gerek Baro bünyesinde, gerek meslekî temsiliyetle kamu kurum ve kuruluşları, sivil toplum örgütleri ve özel hukuk kişileri ile bir arada, birçok çalışmada bulunmuştur. Halihazırda Türk Alman Üniversitesi Sosyal Bilimler Enstitüsü'nde Kamu Hukuku Yüksek Lisans Programı'nın tez aşamasındaki öğrencilerindendir. Almanca ve İngilizce bilir. İstanbul Barosu'nda ilk 5 yıllık kıdemini tamamladıktan sonra, 7255 sicil numarasıyla naklolduğu Adana Barosu'nda, mesleğini, benimsediği değerlerden taviz vermemeye ve her gün kendini geliştirmeye gayret ederek sürdürür.</p>
            
        </div>
    </section>

    <!-- İhtisas Alanlarımız Bölümü -->
    <section class="specialties">
        <h2>İhtisas Alanlarımız</h2>
        <div class="specialties-container">
            <div class="specialty-item">
                <img src="idare.png" alt="İhtisas Alanı 1">
                <p>İdarî faaliyetler sebebiyle maruz kaldığınız haksızlıkların durdurulması, ilgili eylem ve işlemlerin iptali ve bu bağlamda uğradığınız zararların tazmini için gerekli işleri, idârî başvurularınızın ilgili İdâre'ye (kamu kurum ve kuruluşları) yöneltilmesinden, iptal davalarına ve tam yargı davalarına kadar titizlikle yürütüyoruz.</p>
            </div>
            <div class="specialty-item">
                <img src="bireyselbaşvuru.png" alt="İhtisas Alanı 2">
                <p>Anayasa Mahkemesi, Kamu Denetçiliği Kurumu, TİHEK ve Avrupa İnsan Hakları Mahkemesi başta olmak üzere uluslararası yargı organları önünde temel hak ve özgürlüklerinize ilişkin bireysel başvurularınızı her gün daha çok ihtisaslaşarak takip ediyoruz.</p>
            </div>
            <div class="specialty-item">
                <img src="önleme.png" alt="İhtisas Alanı 3">
                <p>Uyuşmazlıkların en kıymetli ve geri getirilemez eşyadan olan vakit başta olmak üzere nelere mâlolabileceğinin şuuruyla, haksızlıklar ve/veya zarar doğmadan yahut derinleşmeden önce "önleme" ilkesinin uygulanmasına çabalıyor, bunun için vazedilmiş hukukî prosedürleri işletiyoruz.</p>
            </div>
        </div>
    </section>

    <!-- Diğer Çalışma Alanlarımız Bölümü -->
<section class="gallery">
    <h2>Diğer Çalışma Alanlarımız</h2>
    <div class="gallery-container">
        <img src="images/1bilisim.png" alt="Bilişim Hukuku">
        <img src="images/2imar.png" alt="İmar Hukuku">
        <img src="images/3is.png" alt="İş Hukuku">
        <img src="images/4kamuihale.png" alt="Kamu İhale Hukuku">
        <img src="images/5ekonomiceza.png" alt="Ekonomik Ceza Hukuku">
        <img src="images/6cocuk.png" alt="Çocuk Hukuku">
        <img src="images/7gayrimenkul.png" alt="Gayrimenkul Hukuku">
        <img src="images/8tazminat.png" alt="Tazminat Hukuku">
        <img src="images/9saglik.png" alt="Sağlık Hukuku">
    </div>
</section>


  <!-- Müracaat Bölümü -->
<section class="application">
    <div class="contact-info">
        <h2>Müracaat</h2>
        <p class="contact-text">Telefon ve e-posta yoluyla ulaşabilir yahut yazıhanemizde veya çevrimiçi yollarla yüz yüze görüşebilirsiniz.</p>
        <p class="contact-text">Mesai saatlerimiz aşağıdaki gibidir. Vakti uymayacak danışanlarımız ve müvekkillerimiz ortak müsait vaktin tayini için talepte bittabi bulunabilirler.</p>
        <p><strong>Av. Nural Kılıç</strong></p>
        <p><strong>Adres:</strong> Toros Mahallesi 78140 Sokak Kapı No.: 2/A Büro No.: 219X Çukurova/ADANA</p>
        <p><strong>E-posta:</strong> av.nuralkilic@gmail.com </p>
        <p><strong>E-posta:</strong> info@nuralkilic.av.tr</p>

        <div class="calendar">
            <h3>Mesai Saatleri:</h3>
            <p>Pazartesi-Salı: 07:00-19:00</p>
            <p>Çarşamba-Perşembe: 07:00-17:00</p>
            <p>Cuma: 07:00-11:00</p>
        </div>
        <button class="show-form-button" onclick="toggleForm()">Randevu Talebi</button>
        <div class="appointment-form" id="appointmentForm">
            <h2>Randevu Talebi Formu</h2>
            <form action="mailto:example@example.com" method="post" enctype="text/plain">
                <label for="name">Adınız:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">E-posta:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Mesaj:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                <button type="submit">Gönder</button>
            </form>
        </div>
    </div>
    <div class="map">
        <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3184.5227986047635!2d35.297360975007344!3d37.04502295386203!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1528895e17a584d9%3A0xca5c5d047e21507c!2sX%20Ofis!5e0!3m2!1str!2str!4v1727352591115!5m2!1str!2str" 
            width="100%" 
            height="450" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy">
        </iframe>
    </div>
</section>




<!-- Footer -->
<footer class="footer">
    <div class="social-media">
        <a href="https://linkedin.com/in/nuralkılıç" target="_blank">LinkedIn: linkedin.com/in/nuralkılıç</a>
    </div>
    <div class="contact-details">
        <p>Toros Mahallesi 78140 Sokak Kapı No.:2/A Büro:219X Çukurova/ADANA</p>
        <p>E-posta: info@nuralkilic.av.tr</p>
        <p>E-posta: av.nuralkilic@gmail.com</p>


    </div>
    <div class="copyright">
        TELİF HAKKI © 2024 AVUKAT NURAL KILIÇ - TÜM HAKLARI SAKLIDIR.
    </div>
</footer>


    <script>
        function toggleForm() {
            var form = document.getElementById('appointmentForm');
            form.style.display = form.style.display === 'none' || form.style.display === '' ? 'block' : 'none';
        }
    </script>

</body>
</html>

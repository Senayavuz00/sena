<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Senanur Yavuz - Kişisel Web Sitesi</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Senanur Yavuz</h1>
        <p>Bilgisayar Mühendisliği Öğrencisi</p>
    </header>
    <nav>
        <a href="#about">Ben Kimim</a>
        <a href="#projects">Projelerim</a>
        <a href="#contact">İletişim</a>
    </nav>
    <main>
        <section id="about">
            <h2>Ben Kimim</h2>
            <div class="about">
                <p>Merhaba! Ben Senanur Yavuz. Bilgisayar mühendisliği öğrencisiyim ve teknolojiye olan ilgimle yazılım geliştirme üzerine çalışıyorum.</p>
                <div class="skills">
                    <div class="skill">C Programlama</div>
                    <div class="skill">Python</div>
                    <div class="skill">Web Geliştirme</div>
                </div>
            </div>
        </section>
        <section id="projects">
            <h2>Projelerim</h2>
            <div class="projects">
                <div class="project">
                    <h3>Hesap Makinesi</h3>
                    <p>Basit bir hesap makinesi uygulaması C diliyle yazılmıştır.</p>
                </div>
                <div class="project">
                    <h3>Web Sayfası Tasarımı</h3>
                    <p>HTML ve CSS kullanarak kişisel bir web sitesi tasarımı.</p>
                </div>
                <div class="project">
                    <h3>Python Veri Analizi</h3>
                    <p>Python ile veri analizi ve görselleştirme projesi.</p>
                </div>
            </div>
        </section>
        <section id="contact">
            <h2>Benimle İletişime Geçin</h2>
            <div class="contact">
                <p>Aklınıza bir proje fikri geldiyse ya da benimle iletişime geçmek isterseniz aşağıdaki formu doldurabilirsiniz:</p>
                <form>
                    <input type="text" name="name" placeholder="Adınız" required>
                    <input type="email" name="email" placeholder="E-posta Adresiniz" required>
                    <textarea name="message" rows="5" placeholder="Mesajınız" required></textarea>
                    <button type="submit">Gönder</button>
                </form>
            </div>
        </section>
    </main>
    <footer>
        <p>© 2025 Senanur Yavuz. | E-posta: senanur.y752@gmail.com</p>
    </footer>
</body>
</html>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hava Durumu Uygulaması</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        p {
            margin-bottom: 10px;
        }
        ul {
            list-style-type: disc;
            margin-bottom: 10px;
            margin-left: 20px;
        }
        code {
            background-color: #f0f0f0;
            padding: 2px 5px;
            border-radius: 3px;
        }
        pre {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>🌤️ Hava Durumu Uygulaması</h1>

    <p>Hava Durumu Uygulaması, kullanıcılara güncel hava durumu bilgilerini sunan bir web uygulamasıdır. Bu proje, JavaScript ve birçok modern web teknolojisi kullanılarak geliştirilmiştir ve kullanıcıların hava durumu verilerini kolayca görüntülemesini sağlar.</p>

    <h2>📋 İçindekiler</h2>
    <ul>
        <li><a href="#özellikler">Özellikler</a></li>
        <li><a href="#kurulum">Kurulum</a></li>
        <li><a href="#kullanım">Kullanım</a></li>
        <li><a href="#proje-yapısı">Proje Yapısı</a></li>
        <li><a href="#katkıda-bulunma">Katkıda Bulunma</a></li>
        <li><a href="#lisans">Lisans</a></li>
        <li><a href="#iletişim">İletişim</a></li>
    </ul>

    <h2>✨ Özellikler</h2>
    <ul>
        <li>🌍 Belirli bir konum için anlık hava durumu bilgileri</li>
        <li>🌡️ Sıcaklık, nem, rüzgar hızı gibi detaylı hava durumu verileri</li>
        <li>🕒 Güncellenmiş verilerin anlık olarak görüntülenmesi</li>
        <li>📊 Kullanıcı dostu arayüz</li>
    </ul>

    <h2>🚀 Kurulum</h2>
    <ol>
        <li>Bu depoyu yerel makinenize klonlayın:
            <pre><code>git clone https://github.com/Hamza-Sengul/havadurumu.git</code></pre>
        </li>
        <li>Proje dizinine gidin:
            <pre><code>cd havadurumu</code></pre>
        </li>
        <li>Bir HTTP sunucusunda projeyi çalıştırın. Örneğin, Python'un <code>http.server</code> modülünü kullanabilirsiniz:
            <pre><code>python -m http.server 8000</code></pre>
        </li>
        <li>Tarayıcınızda <code>http://localhost:8000</code> adresine giderek projeyi görüntüleyin.</li>
    </ol>

    <h2>🛠️ Kullanım</h2>
    <h3>Hava Durumu Bilgisi Görüntüleme</h3>
    <ol>
        <li>Ana sayfada yer alan arama kutusuna şehir veya bölge adını yazın.</li>
        <li>İlgili konumun güncel hava durumu bilgilerini görüntüleyin.</li>
    </ol>

    <h2>📂 Proje Yapısı</h2>
    <p>Proje, genellikle aşağıdaki gibi bir dosya yapısına sahip olabilir:</p>
    <pre><code>havadurumu/
├── index.html
├── script.js
├── style.css
└── images/
    ├── sunny.png
    ├── cloudy.png
    └── ...
    </code></pre>

    <h2>🤝 Katkıda Bulunma</h2>
    <p>Katkıda bulunmak isterseniz lütfen bir <a href="https://github.com/Hamza-Sengul/havadurumu/pulls">pull request</a> açın. Her türlü katkı ve geri bildiriminiz için teşekkür ederiz!</p>

    <h2>📜 Lisans</h2>
    <p>Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için <code>LICENSE</code> dosyasına bakın.</p>

    <h2>📞 İletişim</h2>
    <p>Proje ile ilgili sorularınız veya önerileriniz için lütfen <a href="https://github.com/Hamza-Sengul">Hamza Şengül</a> ile iletişime geçin.</p>

</body>
</html>

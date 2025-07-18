<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Hisse Senedi Fiyat Analizi</title>
</head>
<body>

  <h1>📈 Hisse Senedi Fiyat Analizi</h1>

  <h2>📌 Hisse Senedi Nedir?</h2>
  <p>
    Hisse senedi, bir şirketin sermayesinin eşit paylara bölünmesiyle oluşan ve sahiplerine şirket üzerinde ortaklık hakkı veren menkul kıymetlerdir. Bir hisse senedine sahip olan kişi, o şirketin ortağı sayılır ve şirketin kârından pay alabilir. Hisse senetleri, borsalarda alınıp satılarak yatırımcılara kâr elde etme veya sermaye artışı imkânı sunar.
  </p>

  <h2>🎯 Projenin Amacı</h2>
  <p>
    Bu proje, <strong>Apple Inc. (AAPL)</strong> hisse senedinin geçmiş fiyat verilerini kullanarak:
  </p>
  <ul>
    <li>Verileri indirmek,</li>
    <li>Temel istatistiksel analizler yapmak,</li>
    <li>Kapanış fiyatlarını görselleştirmek,</li>
    <li>20 günlük hareketli ortalama (MA20) hesaplayarak fiyat trendlerini analiz etmek</li>
  </ul>
  <p>
    amaçlanmaktadır. Böylece basit bir hisse senedi fiyat analizi mantığı Python ile gösterilmektedir.
  </p>

  <h2>🛠️ Kullanılan Kütüphaneler</h2>
  <ul>
    <li>pandas</li>
    <li>matplotlib</li>
    <li>yfinance</li>
    <li>warnings</li>
  </ul>

  <h2>⚙️ Nasıl Çalıştırılır?</h2>
  <ol>
    <li><strong>Ortam Kurulumu</strong><br>
      <code>pip install pandas matplotlib yfinance</code>
    </li>
    <li><strong>Defteri Açın</strong><br>
      Jupyter Notebook veya Google Colab ile <code>HisseSenediFiyatAnalizi.ipynb</code> dosyasını açın.
    </li>
    <li><strong>Adımları Takip Edin</strong><br>
      - Veriyi indirin: <code>yf.download()</code> ile hisse verileri çekilir.<br>
      - Veriyi inceleyin: <code>head()</code>, <code>describe()</code> komutları ile genel görünüm.<br>
      - Grafik çizin: Kapanış fiyatlarını ve hareketli ortalamayı görselleştirin.
    </li>
  </ol>

  <h2>📊 Çıktılar</h2>
  <p>
    Bu defteri çalıştırdığınızda:
  </p>
  <ul>
    <li>Apple hissesinin seçili tarih aralığında kapanış fiyatları çizilir.</li>
    <li>Kısa vadeli (20 günlük) hareketli ortalama grafiğe eklenir.</li>
    <li>Fiyat trendini daha anlaşılır görmek için görseller elde edilir.</li>
  </ul>

  <h2>✨ Notlar</h2>
  <p>
    Tarih aralığını ve hisse sembolünü değiştirerek farklı hisse senetleri üzerinde aynı analiz uygulanabilir.<br>
    Bu proje <strong>yatırım tavsiyesi değildir</strong>; sadece temel analiz tekniklerini öğretmek amacıyla hazırlanmıştır.
  </p>

  <h2>📚 Lisans</h2>
  <p>
    Bu proje, eğitim amaçlıdır. Ticari kullanım için uygun değildir.
  </p>

</body>
</html>

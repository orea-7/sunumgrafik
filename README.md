# Daire Atölyesi

5–8. sınıflar için Türkçe, etkileşimli daire grafiği öğrenme aracı.

## Kullanım

`index.html` dosyasını tarayıcıda açın. Kurulum, hesap veya internet bağlantısı gerekmez. GitHub Pages üzerinden de statik site olarak sunulabilir.

## Özellikler

- Kategori, değer ve renk düzenleme
- Fare, dokunma ve klavye ile dilim sınırlarını değiştirme
- Yüzde, merkez açısı ve sadeleştirilmiş kesir gösterimi
- Hazır veri örnekleri, açık/koyu tema ve yerel kayıt
- PNG/SVG dışa aktarma, büyük görünüm ve tam ekran
- Hareket azaltma tercihi desteği

Veri girişinde kategori sayıları düzenlenir. Dağılım modunda komşu iki dilim arasındaki sınır değiştirilir ve toplam değer korunur. Toplam sıfırsa grafik boş durum gösterir.

## Doğrulama

Matematik kontrolleri; toplam yüzde/açı, sıfır değerler, tek kategori, küçük dilimler ve kesir sadeleştirme senaryolarında geçti. Tarayıcı, dokunmatik kullanım ve indirme işlemleri uçtan uca doğrulanmadı.

Veriler yalnızca kullanılan tarayıcının localStorage alanında saklanır.
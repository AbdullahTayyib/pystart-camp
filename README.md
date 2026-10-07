# PyStart Python Kampı

Düzce Üniversitesi Yazılım ve Bilişim Topluluğu'nun 3 haftalık Python kampı. Eğitimi BTK Akademi'den kendi hızında izler, her hafta bir ödev çözer ve çözümünü bu repoya yüklersin.

## Eğitim

Kamp boyunca BTK Akademi'deki **Sıfırdan İleri Seviye Python Programlama** eğitiminin ilk 14 modülünü izleyeceksin.

- [Eğitim sayfası](https://www.btkakademi.gov.tr/portal/course/sifirdan-ileri-seviye-python-programlama-5877)
- [Ders oynatıcı](https://www.btkakademi.gov.tr/portal/course/player/deliver/sifirdan-ileri-seviye-python-programlama-5877)

Eğitim ücretsizdir; izlemek için BTK Akademi hesabıyla giriş yapman gerekir. 15. modül (İleri Seviye Python Modülleri) ve sonrası kamp kapsamında değil.

## Haftalık program

Kamp **11 Ekim 2026 Pazar** günü başlar ve 3 hafta sürer. Ödevlerin son teslim günü her hafta **Cumartesi**.

| Hafta | Modüller | Video süresi | Ödev son teslim |
| --- | --- | --- | --- |
| 1 | 1. Tanıtım<br>2. Gerekli Ortamın Hazırlanması<br>3. Python Objeleri ve Veri Yapıları<br>4. Python Operatörleri | 4 sa 45 dk | 17 Ekim Cumartesi |
| 2 | 5. Koşul İfadeleri<br>6. Döngüler<br>7. Fonksiyonlar | 3 sa 39 dk | 24 Ekim Cumartesi |
| 3 | 8. Nesne Tabanlı Programlama<br>9. Modüller<br>10. Hata ve Hata Yönetimi<br>11. Dosya Yönetimi<br>12. Fonksiyonlarda ileri konular (iç içe fonksiyonlar, decorator)<br>13. Iterators<br>14. Generators | 4 sa 37 dk | 31 Ekim Cumartesi |

Ödev Cumartesi günü teslim edildiği için videoları haftaya yay: günde yaklaşık 45 dakika video ve en az o kadar kod yazma ile haftayı rahat tamamlarsın. 3. modül tek başına 3 saat sürüyor, ilk haftayı son güne bırakma.

## Çalışırken

- **Not al.** Her dersin sonunda öğrendiğini kendi cümlelerinle birkaç satır yaz.
- **Kodu kendin yaz.** Eğitmenin yazdığı her kodu videoyu durdurup kendi bilgisayarında yaz ve çalıştır. Kopyala-yapıştır yapma.

## Ödev süreci

1. Her hafta ödev PDF olarak duyuru kanalında paylaşılır. Son teslim o haftanın Cumartesi günüdür.
2. Çözümlerini `.py` dosyaları olarak yazarsın.
3. Dosyalarını Cumartesi gününe kadar bu repoda kendi adını taşıyan klasöre, **Fork** ve **Pull Request** ile gönderirsin. İkisi de hemen aşağıda anlatılıyor.
4. Ekip Pull Request'ini inceler ve birleştirir (merge). Bundan sonra klasörün bu repoda görünür.

### Fork ve Pull Request nedir?

Bu repo topluluğa ait ve katılımcılar buraya doğrudan dosya ekleyemez. Topluluğun reposunu ortak bir defter gibi düşün: sen o defterin fotokopisini alırsın (fork), ödevini fotokopine yazarsın ve "bunu asıl deftere de ekler misiniz?" diye ekibe gönderirsin (Pull Request).

**Fork**, bu reponun senin GitHub hesabındaki kişisel kopyasıdır. `github.com/yazilimvebilisimtoplulugu/pystart-camp` adresindeki reponun bir eşi `github.com/kullanici-adin/pystart-camp` adresinde oluşur. Kopya tamamen sana aittir: dosya ekleyebilir, silebilir, değiştirebilirsin. Orada yaptıkların topluluğun reposunu etkilemez.

**Pull Request (kısaca PR)**, kendi kopyanda yaptığın değişikliklerin topluluğun reposuna alınması için gönderdiğin istektir. PR açtığında ekip eklediğin dosyaları görür, inceler ve uygun bulursa topluluğun reposuna ekler. Bu son işleme **merge** (birleştirme) denir.

```
Topluluğun reposu
      │  Fork: repoyu kendi hesabına kopyalarsın
      ▼
Senin kopyan (fork)
      │  Ödev dosyalarını yüklersin
      │  Pull Request açarsın
      ▼
Ekip inceler ve birleştirir (merge)
      │
      ▼
Klasörün topluluğun reposunda görünür
```

Neden böyle? Herkes yalnızca kendi kopyasında çalıştığı için kimse yanlışlıkla başkasının ödevini silemez ya da değiştiremez. Açık kaynak projelere de aynı yolla katkı verilir; burada öğrendiğin akışı ileride gerçek projelerde kullanacaksın.

Adımlarda göreceğin bir terim daha var: **Commit**, yaptığın değişikliği kaydetmektir. Dosya yükledikten sonra **Commit changes**'e basmazsan dosyaların kaydedilmez.

### Klasör yapısı

Her katılımcının kendi adıyla bir klasörü, içinde her hafta için ayrı bir klasör olur:

```
ayse-yilmaz/
├── hafta-1/
│   ├── soru1.py
│   └── soru2.py
├── hafta-2/
└── hafta-3/
```

Klasör adını `ad-soyad` biçiminde yaz: küçük harf, boşluk yerine tire, Türkçe karakter yok (`Ayşe Yılmaz` → `ayse-yilmaz`).

### İlk hafta: adım adım

Tüm adımlar tarayıcıdan yapılır, Git kurmana gerek yok.

1. [github.com](https://github.com) üzerinden ücretsiz bir hesap aç.
2. Bu sayfanın sağ üstündeki **Fork** düğmesine, ardından **Create fork**'a tıkla. Repo senin hesabına kopyalanır.
3. Bilgisayarında `ad-soyad` adında bir klasör oluştur, içine `hafta-1` klasörünü aç ve `.py` dosyalarını oraya koy.
4. Kendi forkunda **Add file → Upload files**'a tıkla, `ad-soyad` klasörünü sayfaya sürükleyip bırak ve **Commit changes**'e bas.
5. Forkunun ana sayfasında **Contribute → Open pull request**'e tıkla. Başlığa `Hafta 1 - Ad Soyad` yaz ve **Create pull request**'e bas.

Klasörü sürükleyip bırakamıyorsan: **Add file → Create new file**'a tıkla, dosya adı kutusuna `ad-soyad/hafta-1/soru1.py` yaz (her `/` yeni bir klasör açar) ve kodunu yapıştır.

### Sonraki haftalar

1. Forkunun ana sayfasında **Sync fork → Update branch**'e tıkla.
2. Kendi `ad-soyad` klasörüne gir, **Add file → Upload files** ile yeni haftanın klasörünü (`hafta-2`, `hafta-3`) yükle.
3. `Hafta 2 - Ad Soyad` başlığıyla yeni bir Pull Request aç.

### Dikkat etmen gerekenler

- Yalnızca kendi klasörüne dosya ekle; başkasının klasörüne ve bu README'ye dokunma.
- Bu repo herkese açık. Öğrenci numarası, telefon gibi kişisel bilgilerini dosyalara yazma.
- Gönderdikten sonra düzeltme yapacaksan yeni Pull Request açma. Dosyayı forkunda güncelle; açık olan Pull Request kendiliğinden güncellenir.
- Diğer katılımcıların çözümleri de burada görünür. Bakıp fikir alabilirsin ama kendi çözümünü kendin yaz.

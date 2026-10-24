# Kindle Adam Asmaca

Klasik adam asmaca. Önce kelime yazılır; yazı ekranda görünmez. Sonra harf harf tahmin edilir. Altı yanlışta oyun biter.

Oyun Kindle’ın web tarayıcısında çalışır. EPUB, AZW3 ve KFX JavaScript çalıştırmaz; dosyayı kitap gibi açmayın. Jailbreak gerekmez.

Türkçe ve İngilizce arayüz vardır. Dil, ana sayfanın sağ üstündeki TR ve EN düğmelerinden değişir. Türkçede Türk alfabesi, İngilizcede A–Z kullanılır. Ağ çağrısı ve animasyon yoktur. Oyun açıldıktan sonra uçak modu pile en az yükü bindirir. Kelime tarayıcıya kaydedilmez.

## Kurulum

Kindle’da tarayıcı ayarından JavaScript açık olsun.

### Yazılım 5.16.4 ve sonrası

1. Kindle tarayıcısında şu adresi açın: `https://obilginozi.github.io/kindle-hangman/`
2. Ana sayfa gelince yer imlerine ekleyin.
3. Uçak modunu açın. Yer iminden tekrar açınca oyun internet olmadan gelir.

### Yazılım 5.16.3 ve öncesi

1. Kindle’ı USB ile bilgisayara bağlayın.
2. `index.html` dosyasını Kindle sürücüsünün köküne kopyalayın.
3. Deneysel tarayıcıda `file:///mnt/us/index.html` açın.
4. Yer imlerine ekleyin ve uçak modunu açın.

Bilgisayar ve Kindle aynı Wi-Fi’daysa, bu klasörde `python3 -m http.server 8080` çalıştırıp Kindle’da `http://BILGISAYAR_ADRESI:8080/` açmak da olur.

## Oynanış

1. Yeni oyuna basın.
2. Kelimeyi yazın. Kutu şifre alanıdır; harfler görünmez.
3. Oyuna geçince boş kutular ve harf düğmeleri gelir.
4. Doğru harf, kelimedeki bütün yerlerine yazılır. Yanlış harf çizime bir parça ekler.
5. Altı yanlışta kelime açılır. Bilinince de açılır.

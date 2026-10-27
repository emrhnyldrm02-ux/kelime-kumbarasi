# Kelime Kumbarası

YDS'ye hazırlananlar için İngilizce kelime defteri ve gramer çalışma uygulaması. Tek bir HTML dosyasından oluşur; kurulum gerektirmez.

**Uygulamayı aç:** https://emrhnyldrm02-ux.github.io/kelime-kumbarasi/

## Özellikler

### Kelimeler
- 1.500'den fazla hazır YDS kelimesi; her birinin Türkçe anlamı, örnek cümlesi ve cümlenin çevirisi var
- Kendi kelimeni ekleyebilirsin: anlamı ve örnek cümlesi otomatik bulunur
- Yazdığın kelime çekimliyse 1. haline çevrilir (noticed → notice, went → go)
- Listede zaten olan bir kelimeyi tekrar eklemeye çalışınca uyarır
- Arama, "Öğrendim" işareti, anlamı düzeltme ve sesli okuma (İngilizce)

### Quiz
- Kart çevirmeli quiz; her turda rastgele 20 kelime
- Tüm kelimelerle ya da sadece eklediklerinle çalışma

### Gramer
- Sıfırdan başlayanlar için "Temel Kavramlar" bölümü
- 16 YDS konusu: konu anlatımı, örnek cümleler ve YDS ipuçları
- Açıklamalı YDS tarzı çoktan seçmeli sorular
- İlerleme takibi, "Yanlışlarım" listesi ve konular içinde arama

### Diğer
- Gündüz / Gece / Otomatik tema
- Telefonda da çalışır
- Yedek indirme ve yedekten yükleme

## Kullanım

Uygulamayı yukarıdaki adresten açabilir ya da `Kelime Kumbarasi.html` dosyasını indirip tarayıcıda açabilirsin.

Kelimelerin ve ilerlemen tarayıcında saklanır (localStorage). Başka bir cihaza ya da tarayıcıya geçerken sayfanın altındaki **Yedek indir** ve **Yedekten yükle** butonlarını kullan.

Otomatik çeviri ve örnek cümleler için internet bağlantısı gerekir. Çeviriler [MyMemory](https://mymemory.translated.net/), örnek cümleler ve telaffuz kayıtları [Free Dictionary API](https://dictionaryapi.dev/) üzerinden gelir.

## Yapay zeka kullanımı hakkında

Bu proje, [Claude](https://claude.com) (Anthropic) ile birlikte, "vibe coding" yöntemiyle geliştirilmiştir.
Uygulamanın tasarımı ve kodunun yanı sıra hazır kelime listesi, çeviriler, örnek cümleler,
gramer konu anlatımları ve sorular da büyük ölçüde yapay zeka desteğiyle oluşturuldu;
yönlendirme, karar alma ve test etme tarafımdan yapıldı. İçerikte hata görürsen uygulamadaki
düzenleme butonuyla düzeltebilir ya da bir issue açarak bildirebilirsin. Bunu burada belirtmeyi,
sürecin şeffaf olması açısından önemli buluyorum.

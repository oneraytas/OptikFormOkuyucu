# 🎯 Akıllı Dinamik Optik Okuyucu (Geliştirme Aşamasında)

Bu proje, optik formları bilgisayarlı görü teknikleriyle analiz eden bir sistemdir. Şu an için temel motor (engine) ve hizalama özellikleri aktiftir.
## 🚀 Başlangıç
1. `pip install -r requirements.txt` komutuyla bağımlılıkları yükleyin.
3.  VS code gibi herhangi ide'de Jupyter Notebook Yüklü Olmalı
2. `playground.ipynb` ile motoru test edin.

## Sınav İçin Optik Form Hazırlama
 [+]Biraz manuel bir hazırlama mevcut, optik_form_hazirlama klasörü içerisinde OMRBubbles.ttf adında font var, çift tıkla veya Windows/Font klasörüne yükle.

 [+]Word veya Excelde kendine göre bir dizayn geliştir. Bu kodlar benim geliştirdiğim dizayna göre çalışmaktadır. İlerleyen süreçte dizayn uyumluluğuna bakacağım.
 [+] Form sınavlarda sağ alt köşede bulunmalı. 

## Nasıl Kullanılıyor ? 
 [+] Önce ana klasörde pdfler diye bir klasör yarat. Bu klasör içine tarayıcıdan tarattığın belgeyi/belgeleri koy. 
    Örn; 

 [+]İlk Jupyter hücresini çalıştır. Bu hücre optik_kirpilmis_resimler adında bir klasör oluşturacak ve kırptığı optikleri koyacak

 [+]İkinci Jupyter hücresini çalıştırmadan belki düzenleme yapman gereken şeyler olabilir. Burada değerlendirme işlemini yapacak ve exceli üretecek. Şu anda doğru cevaplar bir dizi içinde tutuluyor burayı istediğin gibi düzenleyebilirsin. Değerlendirme şuan toplam 20 şıklı sorular için. Soru adedi, şekli sonra geliştirilecek. 
 [+] num_colum ve answer_columlar hangi kutucuklar boyalıysa neyle eşleştireceğini belirtiyor. 
 [+] İkinju Jupyter hücresini çalıştırdığında karşına 3 defa pencere gelecek, ilgili alanı doğru seçmen gerekiyor sadece optik alanlar seçilmeli; İlk numara, sonra sol alt ve sağ alt sırasıyla seçilmeli. 
    Örneğin; 
 [+] Oluşturulan excelde iki sayfa var, biri seçtiği şıklar diğeri puanlar; 
    Görüntü;
 [+] 3. Jupyter exceli ise sana doğru işaretlemeyi puanlayabilmişmi onu gösteriyor, klasörde dogrulama_resimleri oluşacak oradaki resimlerde mavi ile çerçeveye alınmış olmalı. 
    Örnek;
    




## 🛠️ Mevcut Özellikler
- [x] **Perspektif Düzeltme:** Siyah kareler üzerinden yamuk taramaları otomatik düzeltme.
- [x] **Dinamik Bölütleme:** Kullanıcı tanımlı satır ve sütun desteği.
- [x] **Excel Entegrasyonu:** Sonuçların ve puanlamanın Excel'e aktarılması.
- [x] **PDF Desteği:** Çok sayfalı PDF'leri işleme.

## 🚧 Yapılacak İşler (To-Do)
- [ ] **Kullanıcı Dostu Arayüz (GUI):** CustomTkinter ile modern bir yönetim paneli.
- [ ] **Sürükle-Bırak Desteği:** PDF'lerin kolayca uygulamaya yüklenmesi.
- [ ] **Gerçek Zamanlı Önizleme:** Seçilen alanların arayüzde anlık gösterilmesi.
- [ ] **EXE Paketleme:** Son kullanıcı için kurulum gerektirmeyen taşınabilir sürüm.


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
<div align="center">
    <img width="633" height="762" alt="image" src="https://github.com/user-attachments/assets/5c7d8ecb-2194-4347-bfbb-d8dd95842e28" />
</div>

 [+]İlk Jupyter hücresini çalıştır. Bu hücre optik_kirpilmis_resimler adında bir klasör oluşturacak ve kırptığı optikleri koyacak
 
    Örn; 
<div align="center">
 <img width="217" height="360" alt="bos_sinav_sayfa_1" src="https://github.com/user-attachments/assets/4f88e618-8a68-4bb0-be6f-f4705a6e16dd" />
</div>
    
 [+]İkinci Jupyter hücresini çalıştırmadan belki düzenleme yapman gereken şeyler olabilir. Burada değerlendirme işlemini yapacak ve exceli üretecek. Şu anda doğru cevaplar bir dizi içinde tutuluyor burayı istediğin gibi düzenleyebilirsin. Değerlendirme şuan toplam 20 şıklı sorular için. Soru adedi, şekli sonra geliştirilecek. 
 
 [+] num_colum ve answer_columlar hangi kutucuklar boyalıysa neyle eşleştireceğini belirtiyor. 
 
 [+] İkinci Jupyter hücresini çalıştırdığında karşına 3 defa pencere gelecek, ilgili alanı doğru seçmen gerekiyor sadece optik alanlar seçilmeli; İlk numara, sonra sol alt cevap ve sağ alt cevap sırasıyla seçilmeli. Fareyle seçim yapıldıktan sonra ENTER tuşuna basılmalı. Bu pencereyi büyütüp küçültmende sorun yok
 
    Örneğin; 
<div align="center">    
    <img width="250" height="220" alt="image" src="https://github.com/user-attachments/assets/b7a28ab5-817f-4973-a94a-b9d2cdd93707" />
</div>
 [+] Oluşturulan excelde iki sayfa var, biri seçtiği şıklar diğeri puanlar; 
 
    Görüntü;
 <div align="center">  
    <img width="800" height="125" alt="image" src="https://github.com/user-attachments/assets/d646e9e7-bb36-4abb-a6a2-ed0d57161238" />
    <img width="800" height="105" alt="image" src="https://github.com/user-attachments/assets/40c095c8-901d-41d1-b204-abff2b10b037" />
  </div>
 [+] 3. Jupyter exceli ise sana doğru işaretlemeyi puanlayabilmişmi onu gösteriyor, klasörde dogrulama_resimleri oluşacak oradaki resimlerde mavi ile çerçeveye alınmış olmalı. 
 
    Örnek;
 <div align="center"> 
    <img width="605" height="280" alt="check_sinav1_sayfa_1" src="https://github.com/user-attachments/assets/9dc47fa4-d4de-41b5-95f6-0f61654a6535" />
</div>
 



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


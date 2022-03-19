# Metin 2 Botu - (OpenCV)

Bu yazılım, Metin 2 oyunu için otomatik metin kesme botu olarak tasarlanmış bir denemedir.

# Nasıl Çalıştırırım?
main.py dosyası eski, onu kullanmanıza gerek yoktur. gui.py üzerinden anlatacağım.

* gui.py dosyasını açıp 107. satırdaki cascade değişkenine cascade.xml dosya yolunu yazın.
* Python yüklü ise CMD ekranını yönetici olarak çalıştırın.
* Dosyaların bulunduğu dizine cd komutu ile gidin
* Ekrana **python gui.py** yazarak enter yapın.
* Oyunda skill barında ki kamerayı saldır olarak değişin.
* Araya basıp oyun ekranını seçin.
* Metin kesme sürenizi yazın ve başlata basın.

# SSS
* **No module named ...** := Adı geçen modül yüklü değil demektir.
* **NameError: name 'wincap' is not defined** := Adı geçen ekran bulunamadı demektir.
* **win32ui.error: BitBlt failed** := Oyunda ekran yakalama engelli demektir.
* **Fare metinin üzerine gidiyor ama tıklamıyor?** := Çözümü hakkında fikrim yok.
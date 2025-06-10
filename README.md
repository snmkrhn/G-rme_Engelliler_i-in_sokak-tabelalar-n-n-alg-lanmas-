# Görme Engelliler İçin Sokak Tabelalarının Algılanması
🔍 Proje Özeti
Bu proje, görme engelli bireylerin şehir içinde karşılaştıkları sokak tabelalarını anlık olarak tanımasını ve sesli uyarılarla yönlendirilmesini amaçlamaktadır. Geleneksel yapay zekâ sistemlerinin aksine, bu sistem federated learning (dağıtık öğrenme) mimarisi üzerine kurulmuştur. Böylece kullanıcıların görüntü verileri cihazlarında kalır, gizlilik korunur ve yalnızca model ağırlıkları merkezi sunucuya iletilir.

🎯 Amaç
Görme engellilerin şehir içi yön bulmalarını kolaylaştırmak.
Sokak tabelalarını kamera görüntüsüyle tanıyıp sesli olarak ifade etmek.
Kullanıcı verisini merkezi sunuculara göndermeden öğrenme gerçekleştirmek.
Veri gizliliğini koruyarak etik yapay zekâ kullanımı sağlamak.

🛠️ Kullanılan Teknolojiler
Python
OpenCV – Görüntü yakalama ve işleme
YOLOv8 – Sokak tabelası nesne tespiti
Tesseract OCR – Metin tanıma
gTTS (Google Text-to-Speech) – Sesli geri bildirim
Federated Learning (FLwr) – Dağıtık model güncellemesi
Google Colab + Local PC – Eğitim ve test ortamı

# ReadMe!!!

PyTest nedir ?

Pytest, Python dilinde popüler bir test çerçevesidir. Yazılım testi sırasında, bir programın doğru çalışıp çalışmadığını, beklendiği gibi çalışıp çalışmadığını ve belirlenmiş gereksinimleri karşılayıp karşılamadığını belirlemek için kullanılır. 
Pytest, diğer test çerçevelerine göre daha okunaklı ve kullanımı daha kolaydır. Pytest, test fonksiyonlarını otomatik olarak algılayabilir ve test sonuçlarını raporlayabilir. Ayrıca, pytest, testleri sıralamak, testleri yürütmek ve test sonuçlarını görselleştirmek için birçok farklı eklenti sunar. Bu özellikleri sayesinde, pytest, yazılım testleri yapmak için sıklıkla kullanılan bir araçtır.

 Decorator nedir ?

 Dekoratör, Python programlama dilinde bir fonksiyonu veya sınıfı işlevselliğini değiştiren veya genişleten bir işlevdir. Dekoratörler, işlevleri değiştirmek için kullanılan işlevsel programlama tekniklerinden biridir.

 Dekoratörler, bir işlevin başka bir işlev tarafından "sarmalanması" anlamına gelir. Bir işlevi saran dekoratör işlevi, orijinal işlevin çalışması öncesinde veya sonrasında ek işlemler gerçekleştirebilir veya orijinal işlevin sonucunu değiştirebilir. Bu, kodun tekrar kullanılabilirliğini artırır ve işlevleri modüler hale getirir.

 Dekoratörler @decorator sözdizimi kullanılarak işlev veya sınıfların üzerine yerleştirilir ve dekoratör işlevi, işlevin yürütülmesi öncesinde veya sonrasında ek işlemler yaparak orijinal işlevin davranışını değiştirir.

 PyTestdeki decoratorleri nelerdir ?

 pytest'ta kullanılan bazı yaygın test dekoratörleri şunlardır:

 1- @pytest.fixture: Testler arasında paylaşılan öğeleri (nesneler, bağımlılıklar vb.) hazırlar. Yani bir testin çalışması için gereken önceden koşulların             hazırlanmasına yardımcı olur.

 2-@pytest.mark.parametrize: Bir test fonksiyonunu farklı parametre değerleriyle tekrar tekrar çalıştırır.

 3-@pytest.mark.skip: Belirli bir testi atlamak için kullanılır.

 4-@pytest.mark.xfail: Testin geçmesi beklenmeyen ve hatalı sonuçlar vermesi beklenen durumlarda kullanılır.

 5-@pytest.mark.timeout: Bir testin belirli bir süre içinde çalışmasını sağlar ve belirtilen sürenin üzerine çıktığında testi durdurur.

 6-@pytest.mark.dependency: Testler arasında bağımlılıklar belirlemek için kullanılır.

 7-@pytest.mark.usefixtures: Test fonksiyonlarına, belirli bir fixture'ı otomatik olarak eklemek için kullanılır.

 Bu dekoratörler, testlerin belirli bir şekilde çalışmasını ve sonuçlarının raporlanmasını sağlar.
 
![Ekran Görüntüsü (28)](https://user-images.githubusercontent.com/120026505/229372107-a7c1ffc8-42f6-454c-87b9-3da69f909a51.png)
![Ekran Görüntüsü (27)](https://user-images.githubusercontent.com/120026505/229372229-36f98703-19b3-4b56-8508-de0e6ccb0481.png)

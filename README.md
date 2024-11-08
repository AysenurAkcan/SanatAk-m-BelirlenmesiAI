## Sanat Eserlerinde Akımın Belirlenmesi

## Proje Özeti
Bu proje, sanat eserlerinin görüntülerinden Kübizm, Empresyonizm, Ekspresyonizm, Realizm, Surrealizm akımlarını belirlemek için bir yapay zeka modeli geliştirmeyi amaçlamaktadır. Çeşitli web kaynaklarından veri çekilerek veriler toplanıp akımlara uygun olmayan verilerin elenmesiyle veri seti oluşturulmuştur ve görüntülerin doğru sınıflandırılabilmesi için veri setinde döndürme, parlaklık değiştirme, yansıma ve satürasyon gibi veri artırma teknikleri görüntülerde rastgele kullanılmıştır.

## Geliştirme Ortamı
-**Jupyter Notebook**: IDE
-**Python**: Programlama Dili

## Kütüphaneler
  -**Web Scraping**
  -Selenium: Dinamik sayfalardan veri çekme için selenium kütüphanesi tercih edilmiştir.
  Requets: Selenium kütüphanesiyle beraber requets kütüphanesi çekilen verileri indirme işlemi için kullanılmıştır.
  -**Görüntü İşleme**:  
  -OpenCV: Döndürme, parlaklık değiştirme, yansıma ve satürasyon görüntü işlemelerini gerçekleştirme için kullanılmıştır.
  -Pillow: Çeklilen görüntülerde akımların içerisinde bulunabilecek aynı görüntülerin, pHash değerinin tespit edilip ikililiği kaldırma işlemi yapılmıştır.
  
## Sonuç ve Değerlendirme
İsterlere göre uygun görüntü verileri toplanıp veri seti oluşturarak modelleme kısmı için olup görüntü işlemeyle temel oluşturulmuştur.

  



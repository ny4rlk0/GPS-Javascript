# GPS-Javascript
GPS-Javascript-GoogleMaps

https://www.nyarlko.com/ibb (Kapatılabilir.)

veritabani.json içerisini gitmek istediğiniz konumların adreslerini ekleyin.
Dakikayı girin.
Dakika içinde gidebileceğiniz adreslerin yol tarifini haritadan alın.
Google api keyini kendi api keyinizle değiştirin.

Sistemin 2 modu var:

1. Otomatik olarak konumu tespit ediyor. (Bu modda başlıyor zaten.)

2.Adresi elle girme modunu seçerseniz yukarıda girdiğiniz adresi başlangıç noktası olarak alıyor.

Şu an mevcut olarak IBB binasını test konumu olarak seçtiğim için veri tabanıma oranın yakınındaki 10 konumu ekledim. ( 1dk ile 60 dk arasında konumlar var.)


Otomatik konumda ;

Veri tabanındaki konumların hepsini uzaklık olarak hesaplıyor rota çıkarıyor daha sonra gidiş süresi verilen dakikadan fazla olan süreleri çıkarıp ekranda rotaları gösteriyor.

Test Seçenekleri:

Adresi elle girme modunu seçin>Adresi yukarı yazın>Rotaları Hesapla 'ya tıklayın.

Otomatik konumu seçin>İlk sefere özgü konum izni verin>Rotaları hesapla'ya tıkla.

Not: Konum izni vermeyecekseniz adresi elle bulma modu seçili iken Rotaları hesaplaya basmanız gerekiyor.

Not2: Eğer yazdığınız dakikada gidebileceğiniz konum veri tabanında yoksa sonuç vermez.
(veritabani.json)

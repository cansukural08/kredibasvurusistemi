# kredibasvurusistemi
Kredi skoruna göre kişiye kredi limitini hesaplayan proje

Bu projede; kullanıcıdan isim, soyisim, TC Kimlik bilgileri, telefon ve istenilen kredi bilgileri alınarak kişiye ilgili kredi notuna göre kredi limiti çıkartılır.
Eğer kişinin kredi notu 500'den aşağıdaysa, kredi isteği onaylanmaz ve kişi red cevabını alır.
Eğer kişinin kredi notu 500 ve 1000 arasında ve geliri 5000'den aşağıdaysa, kişinin kredi isteği onaylanır ve kişiye 1000 TRY kredi limiti tanımlanır.
Eğer kişinin kredi notu 1000 den yukarıdaysa, kişinin kredi isteği onaylanır ve kişiye gelirinin kredi risk çarpanı katı kadar (4 katı) kredi limiti tanımlanır.

Projeyi zip dosyası olarak indirip çalıştırabilirsiniz. Proje Apache NetBeans 11.1 IDE'sinde yazılmıştır. 

Proje geliştirilirken java kullanılmış olup, önyüzde JSF'den yararlanılmıştır. XHTML uzantılı dosyaların içerisinde JSF kodları bulunmaktadır.


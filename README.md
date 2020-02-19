# BlackJack

06 — Elleri Göster fonksiyonunun yeniden düzenlenmesi
Şimdi, herhangi bir eli gösterebilmek için ShowHands fonksiyonundaki birkaç tekrarlanan adımı yeniden düzenleyin.

1. ShowHands fonksiyonunu ShowHand olarak yeniden adlandırın ve iki parametre ekleyin: hand and score. Daha sonra her elin değerini hesaplarken score parametresini kullanırsınız.
2. playerCards ve dealerCards değişkenlerini cards isimli bir degiskenle değiştirin.
3. dealer dizisi üzerinden yinelenen döngüyü silin.
4. hand parametresi üzerinde yineleme yapmak ve kartları cards değişkeninde saklamak için player dizisi üzerinden yineleme döngüsünü değiştirin.
5. cards dizesini bir boşluk karakteri ve score parametresindeki değerle birleştirin ve dizenin sonuna yeni satır karakteri ekleyin. Değeri, outputArea öğesinde zaten var olan değerle birleştirerek sonucu görüntüleyin.
6. Değiştirilen ShowHand fonksiyonunu çağırmak için delaer dizisini ve skor parametresi için null değerini iletmek üzere ShowHands fonksiyon çağrısını değiştirin.
7. ShowHand fonksiyonuna başka bir çağrı ekleyin ve player dizisini ve null değerini iletin.
8. Eller görüntülenmeden önce oyun tablosunu temizlemek için ClearTable adında parametresiz yeni bir fonksiyon ekleyin. Bunu yapmazsanız, bir sonraki el mevcut elin bir parçası olur.
9. outputArea öğesine boş bir string atayın.
10. dealInitialCards fonksiyonunun üst kısmındaki ClearTable fonksiyonunu çağırın.
11. Tüm değişiklikleri kaydedin ve tarayıcının, kartları player ve dealer ellerinde olduğu gibive kartların yanında null değer bulunduğunu doğrulayın.

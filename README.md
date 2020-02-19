# BlackJack

05 - Elleri Göster
Artık desteyi karıştırıp ondan kart çekebileceğinize göre, oyuncu ve dağıtıcı için ilk iki kartı çeken ve tarayıcıda görüntüleyen işlevsellik ekleme zamanı gelmiştir.

1. Deck dizisinin altına dealer ve player adı verilen iki boş dizi ekleyin.
2. output-area alanını, az önce eklediğiniz iki dizinin altındaki outputArea adlı bir değişkende önbelleğe alın. Bir öğenin önbelleğe alınması, tarayıcı her zaman DOM'daki öğeyi aramak zorunda olmadığından performansı artırabilir.
3. Tarayıcıda veri görüntüleyen JS dosyasının sonundaki kodu kaldırın.
4. JS dosyasının sonunda hiçbir parametresi olmayan showHands adlı yeni bir fonksiyon ekleyin.
5. Fonksiyonun içinde, player dizisinin üzerine gelin ve her kartın karakterini (kartın card özelliğinden) playerCards adlı bir string değişkene ekleyin.
6. Dealer dizisi için önceki adımı tekrarlayın ve sonucu dealerCards adlı bir string değişkende saklayın.
7. dealerCards stringini, arasında yeni satır karakteri olan playerCards stringi birleştirin ve daha önce oluşturduğunuz outputArea değişkenini kullanarak sonucu görüntüleyin.
8. showHands işlevinin altında parametresi olmayan dealInitialCards adlı başka bir fonksiyon oluşturun.
9. Fonksiyon içinde, dealer için drawCard işlevini iki kez çağırın ve kartları player dizisine ekleyin.
10. Player dizisi için önceki adımı tekrarlayın.

11. dealInitialCards fonksiyonunun sonunda oluşturduğunuz ShowHands fonksiyonunu çağırın.
12. İşlevin altındaki dealInitialCards fonksiyonunu çağırın. Kodu kaydedin ve tarayıcının dealer için iki kart ve player için iki kart gösterdiğini doğrulayın.

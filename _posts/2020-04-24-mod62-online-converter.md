---
layout: post
title: Mod62 Online Converter
categories: update
date: 2020-04-24T07:42:00.000Z
---
<img src="/images/fulls/2020-04-24-mod62-online-converter.png" class="fit image">
**Artık kodu çalıştırmak için bilgisayarı açmaktan kurtuldum.**<br>
[Mod62 Çevrimiçi Dönüştürücü](https://muaz742.com/mod62) ile anında test edebiliyorum.

Geçenlerde Mod62 üzerine düşünürken şöyle bir not aldım;<br>
*"mod62 online converter"*

Bu sefer aciliyeti yoktu. Bir ara yaparım tonunda bir satır görevdi sadece. Orman'ı [revize](https://sozluk.gov.tr/?kelime=revize) ettiğim bu süreçte Mod62'nin PHP yapısını JavaScript'e çevirmem gerekiyordu. Aynı işlem adımlarını JavaScript ile yazdım. Hatta işlem adımlarına o kadar sadık kaldım ki PHP dilindeki [*array_flip()*](https://www.php.net/manual/tr/function.array-flip.php) fonksiyonunu olduğu gibi JavaScript üzerinde kullanmak için satır arasına yeni bir [fonksiyon](https://stackoverflow.com/questions/1159277/javascript-equivalent-of-php-function-array-flip) bile ekledim. Artık [mod62.js] göreve hazır biçimde gelişime açıktı.

Gündelik hayatta konu Mod62'ye geldiğinde ne yaptığını basitçe anlatmakta zorluk çektim. Empati yaptığımda gayet kafa karıştırıcı olduğunun da farkındayım. Muhabbet etmek hoş fakat Mod62'nin ne olduğunun anlatım ve anlaşılma sürecinde harcadığım vakit gözüme batmaya başladı. Aktarıma yardımcı bir çözüm ile bu vakti kısaltmanın bir yolunu bulmam gerekliydi. Bunu nasıl yapacağımı düşünürken Ziya Paşa'nın [*"Ayinesi iştir kişinin lâfa bakılmaz"*](https://tr.wikiquote.org/wiki/Ziya_Pa%C5%9Fa) sözünden ilham aldım. Mod62 sınıfının ne yaptığını canlı olarak göstermeye karar verdim. Notumu aldım. Bunu yaptığımda ne olduğunu anlatmak zorunda kalmadan Mod62'nin işini doğrudan gösterebilecektim.

Her şey güzel, yapılacak işin netleşmesi ile içim huzurlu biçimde yaşamıma devam ediyordum. Gündelik yaşamda konunun Mod62'ye gelmesi, ardından ne olduğunu anlamak isteyen bir soru gelmesi ihtimali gayet düşüktü. Bu sebeple bu görev, önceliği düşük bir değere sahip oluyordu. Ara sıra bu ekranın nasıl olması gerektiğini yüzeysel olarak düşünüyordum. Fakat yapılacaklar listemde aynı satırın bir kaç gün boyunca orada kaldığını görmek içimi acayip sıktı. Dayanamadım. Yaptım. Hatta en üste anahtar setini elle ayarlanabildiği bir kısım da ekledim. Mesela sınıfın hesaplama yaparken kullanmasını istediğin anahtar setine "01" yazdığında çevirmesini istediğin sayının [Binary](https://tr.wikipedia.org/wiki/%C4%B0kili_say%C4%B1_sistemi) karşılığını bile görebilirsin. "10" yazarsan da ters ifadeler ile sonuç verecektir. Bu arada tabii ki büyük sayı ve işlemleri hesaplamayacaktır. Seni deneyip vakit kaybetmekten kurtarayım. Bunu ufak tefek kod çevirme işlemlerini pratik biçimde yapabilmesi için tasarladığımı hatırlatır, daha iyisini yapmak istersen geliştirmelerini beklerim. Denemek istersen sayfanın başındaki bağlantıdan ulaşabilirsin.
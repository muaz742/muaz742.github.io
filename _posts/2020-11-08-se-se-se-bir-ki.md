---
layout: post
title: Se Se Ses Bir Ki
categories: update
date: 2020-11-08T16:30:00.000Z
---
<img src="/images/fulls/2020-11-08-se-se-se-bir-ki.png" class="fit image">

**Python ile text-to-speech kütüphaneleri kullanım çalışmamda oluşan kayıtların bulunduğu depo.**<br>
[Se se ses bir ki][depo] ile kolayca dönüştürme yapabiliyorum.

Geçenlerde okuyor olduğum bölümün Algoritma ve Programlama dersini Python ile işlemeye başladık. Python dili benim için epeydir uzaktan gözlemlediğim, ara sıra kodlarına bakıp, bir şeyler deneyip uzaklaştığım bir dildi. Basitçe işim düşmediği için uğramadığım ama ara sıra da selam verip geçtiğim bir komşum gibiydi. Kullandığım dillere göre farklı bir yazım tarzı vardı. Yeni bir dilin kullanımını öğrenmek, kullandığım diğer diller ile iletişimimi olumsuz etkiler mi endişesi ile uzak kaldım. Kaygımın yerli mi yoksa yersiz mi olduğunu düşünmeksizin aldığım ders ile bu dilden sorumlu olduğum için mutluyum. Böylelikle biraz Python kodları kurcalamaya sebep buldum. 

Derken Python ile pratik yapmak için bir sebebe ihtiyaç hissettim. Bu dil kullanımı üzerine pratik yapmalıydım. Bundan birkaç ay önce, yazılımla ilgilenen birkaç arkadaşıma muhabbet arasında **“bu videolardaki sesleri yazılımla yazıya dönüştürsek mi?”** diye bir soru yöneltmiş ve sonucu olan bir yanıt alamamıştım. Sürecin devamında videolar yarı otomatik, yarı manuel biçimde yazıya dönüştürülme işlemi gördü ve sonuç pek verimli olmadı ama konumuz bu değil. Sonuçta bir süreç içerisinde böyle bir işleme ihtiyacım oldu ve **bu işlemi yazılımla uygulama yeteneğine sahip değildim.** Bu benim için **güzel bir fırsat yeterli bir sebepti.** Ben de ülkemizin düğün gibi kültürel etkinliklerde kullanılan, teknik nitelikli kişilerin toplumda seslerini güçlü şekilde duyurabildikleri **geleneksel ses sistemi test ifadeleri**nden (se, se, ses 1, 2, ses kontrol) ilham alarak içerisinde çalışmak için klasör oluşturdum. 

Edindiğim motivasyon ile astronot kıyafetlerimi giyip uzay kaskımı taktıktan sonra geri sayım başladı ve o sihirli kelimeleri Google motorunda aradım… *“how to convert sound file to text on python”*

İlk adımda [Google TTS][gtts] ile yazdığım metni ses dosyasına dönüştürdüm. Bütün işlem 3 satırda bitti. Basitçe, metni seçip Google sunucularına gönderiyordum. Gelen yanıtı bir ‘.mp3’ dosyasına kayıt ediyordum. Tatmin olmadım. Mikrofonun algıladığı ses sinyallerini anlamlandıran ve bu anlamları kelimelere dönüştüren bir program yazmak gibi bir telaşa girerek ayı yeniden keşfetmeye de ihtiyacım yoktu. **Tıkladığım zaman kolayca işlemi yerine getiren bir araca**    dönüştürmem yeterliydi. Evet, işin fiyakalı kısmını Google sunucuları işliyor ve ben sadece internette bulduğum dokümanlara göre komutlar yazıyordum. Kabaca Lego oynamaktan farklı değildi yaptığım. Ama parçaları tanımak için mükemmel fırsattı. 

İkinci adımda ses dosyasını yazıya dönüştürme işlemini tamamladım. Bunun için [Python ile Ses Tanıma Uygulaması Oluşturma][kaynak0] ve [How to Convert Speech to Text in Python][kaynak1] kaynaklarındaki yönergeleri takip ettim. Her şey güzel, hoş ve yetersizdi. Harcadığım vakti öğrendiklerimle kıyasladığımda tatmin olamıyordum. Bilmediğim bir dil üzerinde bir amaç ile ilerlerken terminalde **hata mesajını görmek istiyordum.** Böylelikle odağımı bir konu üzerine yoğunlaştırmak, o **sorunun çözümünü öğrenme fırsatı** yakalamak istiyordum. Neyse ki henüz işim bitmemişti.

Üçüncü adımda bu işlemlerin kolaylaştırmaya odaklandım. Bu süreçte Python ile **dosya seç**imi, seçilen **dosyaların tiplerini** sınırlandırma, **Unix zaman** değerini oluşturma, yeni bir **dosya oluşturma**, oluşturulan dosyayı **Türkçe dil desteği** ile kaydetme gibi birkaç konuda işlemlerin uygulanmasını deneyimledim. Artık kullanıma hazırdı. Hiç kodlarla uğraşmadan terminal üzerinde çalışan bir program ile **“metni ses dosyasına dönüştürme”** ve **“ses dosyasını metne dönüştürme”** işlemlerini uygulayabiliyordum. Buna mikrofondan gelen sesi metne çevirme gibi seçeneklerde eklenebilir fakat harcadığım vaktin öğrendiklerime değdiğini hissettiğim gibi sonraki adıma geçmeye karar verdim.

Dördüncü adımda kodlarımı geliştiriciler için yalınlaştırdım. Aynı zamanda bir süre sonra tekrar bakıp **“ben burada ne yapmışım acaba”** diyen kendim için de işleri kolaylaştırmış oldum. rehberlik sağlaması için **“işlev, girdi, çıktı, işlem adımları, kullandığım kaynaklar”** başlıklarını kodların ilk satırlarına ekledim. Çalışma klasörümü temizledim. Bu çalışma alanı için bir [rehber doküman][readmeDepo] hazırladım. Kayıtları, GitHub deposu oluşturdum ve içerisine ekledim. Sonunda çalışmayı bilgisayarımdan silebildim. Artık ihtiyaç duyduğumda kolayca indirebilirim.

Python dilinin [girintiler ile katmanlar oluşturma][indentasyonPython] gibi diğer dillere olan yazım farklarının verdiği tedirginliğe rağmen yalınlığıyla ayrı bir çekiciliği var. Hoş bir deneyimdi. Eğer sen de kodlara göz atmak veya birkaç parça geliştirme eklemek istersen **yazının başlangıcındaki bağlantıdan** ilgili depoya ulaşabilirsin.

[depo]:(https://github.com/muaz742/se-se-ses-bir-ki) "Se se ses bir ki GitHub Deposu"
[gtts]:(https://pypi.org/project/gTTS/) "gTTS · PyPI"
[kaynak0]:(https://medium.com/bili%C5%9Fim-hareketi/python-ile-ses-tan%C4%B1ma-uygulamas%C4%B1-olu%C5%9Fturma-3d0d972c62a6) "Python ile Ses Tanıma Uygulaması Oluşturma"
[kaynak1]:(https://www.thepythoncode.com/article/using-speech-recognition-to-convert-speech-to-text-python) "How to Convert Speech to Text in Python"
[readmeDepo]:(https://github.com/muaz742/se-se-ses-bir-ki/blob/main/README.md) "Beni Oku - Se Se Ses Bir Ki"
[indentasyonPython]:(https://www.w3schools.com/python/gloss_python_indentation.asp) "Python Indentation"
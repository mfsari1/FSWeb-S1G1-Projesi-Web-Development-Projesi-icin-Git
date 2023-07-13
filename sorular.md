# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Herhangi bir kodu ve yazilimi, versiyonlar halinde gelistirmeye ve yapilan gelistirme/degisiklikleri tracking etmeye olanak saglayan bir version control sytem'dir.

2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemi iken, Github bir online repo hosting servisidir.
Git localde calisirken, github cloud-based'dir.
Git branch modellemesi ile programda degisiklik yapilmasini saglarken, github online olarak baskalariyla yapilan degisikleri paylasip, duzenlemeleri online olarak takip etmeye yardimci olur.

3. Neden bir branch oluşturuyoruz?
Yeni bir feature ya da patch eklemek istedigimizde, ve main branch uzerinde henuz bir degisiklik yapmadan branch ile yapilacak feature duzenlenip commit edilip pushlanip kontroller yapildiktan sonra main branch'a mergelenmesi, branchlar ile feature ekleme surecini takip ederek, gerekli kontrollerin yapilarak programda bir degisikligin saglikli sekilde yonetilmesini saglar.

4. Pull Request'in amacı nedir?
Pull requests ile main branch'a yapilacak olasi bir merge oncesi, takim arkadaslarina bilgi vererek olasi degisiklikleri ve branch uzerindeki commitleri inceleyip kontrol edilir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout komutu ile branchler arasinda switch yapabiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch ile github'da(remote repoda)ki yeni bir guncelleme oldugu durumda ve bunu lokal'e almak istediginde, git fetch komutu ile lokal'e alip daha sonrasinda ise git merge komutu ile lokal bilgisayarinda klasorleri arasinda goruntuleyebilir. 

7. Merge conflict nedir?
Merge conflict bir dosyada ayni satirda bir kisinin duzenledigi bir kismi baska birisinin silmesinden dolayi olusur.

8. Merge conflict'i nasıl çözeriz?
Merge conflict olan dosyada conflict marker ile belirtilen kisimda hangi degisikligin kalmasi gerektigine karar verip, degisiklikleri ekleyip, commitleyebiliriz.

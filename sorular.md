# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git kod depolamaya, yapılan değişiklerin izlenmesine, bu değişikliklerin bir araya getirilmesine veya değişiklik yapılmadan önceki haline geri dönülmesine izin veren ve bunu sağlayan açık kaynaklı bir sürüm kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

Bir yazılım olan Git, sistemde yerel olarak kurulan bir komut satırı aracıdır. Grafiksel bir kullanıcı arayüzü olan GitHub ise Git depoları için web tabanlı bir barındırma hizmetidir.

3. Neden bir branch oluşturuyoruz?

Yeni özellikler geliştirmek ve daha sonrasında bunları merge komutu ile birleştirmek için branch oluşturulur.

4. Pull Request'in amacı nedir?

GitHub'daki bir depodaki(repodaki) bir branch'e gönderdiğiniz değişiklikleri başkalarına söylemenize olanak tanır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Git branch komutu ile mevcut branchleri listeleyebiliriz. Bir branchten diğer branch'e geçmek için ise checkout komutunu kullanmalıyız. Main branch'ine geçmek için ise git checkout main komutunu yazmalıyız.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Git fetch, uzak bir depodan içerik indirmek için kullanılan birincil komuttur. Git merge, Git'in çatallanmış bir geçmişini birleştirmeyi sağlar. Git pull, verilen parametreler ile git fetch'i çalıştırır. Ayrıca, git pull uzak bir depodan içerik getirir, indirir ve değişiklikleri yerel depoya entegre eder.  

7. Merge conflict nedir?

Merge conflict, Git'in iki işlem arasındaki kod farklarını çözemediği durumlarda gerçekleşen bir durumdur.

8. Merge conflict'i nasıl çözeriz?

Merge conflict'i çözmek için öncelikle çakışan veya farklılık gösteren dosyayı açıp gerekli değişiklikleri yapmak gerekir. Bu işlemden sonra git add komutu ile yeni birleştirilmiş(merge) içerik hazırlanır. Son olarak git commit komutu ile yeni bir commit oluşturulur.

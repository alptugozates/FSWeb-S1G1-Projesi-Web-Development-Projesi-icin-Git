# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Projemizi riske atmadan başka bir versiyonunu kullanarak üzerinde çalışırız. Herhangi bir hata sonucunda ise bir önceki orjinal versiyonumuza sorunsuzca dönüş yapabiliriz.
2. Git ile GitHub arasında ne fark var?
Git yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Github ise bir kod deposudur. Dünyanın farklı ülkelerinden developerlar belirli projelere, belirli kişileri ekleyerek birlikte takım çalışması yapılabilmesine olanak sağlar.
3. Neden bir branch oluşturuyoruz?
Projemizin o anki halini bozmamak için oluştururuz. Farklı versiyonlarına erişmemizi sağlar. Developer o an projeye bir yenilik eklemek istediğinde, yapılan değişiklik projeyi olumsuz etkileyebilir. Bunun gibi durumların önüne geçilmesi için oluşturuyoruz.
4. Pull Request'in amacı nedir?
Branch'ten sorumlu developerdan kodumuzu ekleme talebidir. Ayrıca branch'ten sorumlu developer neyi değiştirdiğimizi görmesine yardımcı olur.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
Bir branch'ten diğerine geçmek için 'git checkout dosya adı'. Main Branch'e dönmek için ise git checkout 'main'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch, başkalarının servera yüklediği tüm yeni işlemleri indirir. git merge, kendi branch'imizde yaptığımız tüm işlemleri Master Branch ile birleştirme, entegre etme işlemidir. git pull, master branch'teki yapılan değişiklikleri local'a çekmemize olanak sağlar. git fetch bütün dosyaları indirip entegre etmediğinden herhangi bir çakışma yaratmaz. git pull'da ise master branch'teki yapılan değişiklikleri kaydeder ve bunları birleştirir, çakışmalar yaratır. git merge ise farklı olarak ayrı branch'te yapılan çalışmaları master branch'e entegre eder.
7. Merge conflict nedir?
İki kişi veya daha fazla kişinin aynı satırı veya dosyayı değiştirmesi durumunda git bunu merge edemezse, conflict yani çakışma olacaktır
8. Merge conflict'i nasıl çözeriz?
Çakışma yaşayan developerın tekrardan dosyayı açıp çakışma olan yerleri bulup manuel olarak düzeltmesi gerekir. Daha sonra sorunu hallettikten sonra git'e tekrar merge yapması gerekir.

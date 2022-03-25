# GİT KOMUTLARI

## Terminal Komutları

#### ls => İçinde bulunduğumuz klasörleri ve dökümanları gösterir.
#### ls -la => Gizli klasörleri gösterir.
#### pwd => Hangi klasörde bulunduğumuzu gösterir.
#### cd => Gitmek istediğimiz klasöre konumlandırır.
#### cd .. => Bir önceki klasöre götürür.
#### clear => Ekranı temizler.
#### mkdir => Klasör oluşturur.
#### touch => Dosya oluşturur, dosya.txt, index.html gibi.
#### rm => Dosyayı kaldırır, siler.
#### rm -rf => Klasörü kaldırır, siler.

## Git Komutları

*NOT => 1-) untracked (izlenmeyen): GIT tarafından henüz takip edilmeyen, yani yeni oluşturulmuş dosyaları ifade eder.
2-) unstaged (hazırlanmamış): Güncellenmiş ancak commit’lenmek için hazırlanmamış dosyaları ifade eder.
3-)staged (hazırlanmış): Commit’lenmeye hazır olan dosyaları ifade eder.
4-)deleted (silinmiş): Projeden silinmiş ama GIT üzerinden kaldırılmamış dosyaları ifade eder.

#### git config --global user.name "AD"
#### git config --glabal user.email "EMAİL"
#### Adı gösterir => git config user.name
#### Email gösterir => git config user.email
####  git config --list => Bu ayarların bütününü görüntüler.
#### git status => Git'in güncel durumunu gösterir.Üzerinde çalışılan projenin o anki durumu hakkında bilgi verir. Yapılan değişiklikler, eklenen ve silinen dosyalar gibi bilgiler listelenir.
#### git init => Git'e bağlamak, git'i klasörde aktif etmek için ve içerisinde kullanılabilecek bir yazılı, çizili vs belgeyi takip etmek için kullanılır.Henüz versiyon kontrolü altında olmayan bir projenin dizininde, boş bir git deposu oluşturmak için kullanılır.
#### git add . => Dosyaları dizine ekler ve commitlemeye hazır hale getirir. Mevcut dizindeki tüm dosyaları dizine ekler.Yeni eklenen veya üzerinde değişiklik yapılan dosyaları staged ortamına göndermek için kullanılır.
#### git commit -m "Mesaj" => Git'e eklediğimiz dosyaları kalıcı olarak git veri tabanına işler.Commit, staged ortamına alınan dosyaların Local Repository’e gönderilmesidir.
#### git log => İşlem yapılan commitleri gösterir.Projedeki commit geçmişini görüntülememizi sağlar. Bütün commit'ler, id'si, yazarı, tarihi ve mesajı ile beraber listelenir.
#### gitignore => Bazı uzantı veya dizindeki dosyaların git'e gönderilmesini engellemek amacıyla oluşturulur, uzantı dosyasını içine yazarak uygulanır.
#### git branch => Yeni bir branch açmak için kullanılır.Local veya remote repository üzerinde yeni bir branch (dal) eklemek, silmek veya listelemek için kullanılır.
#### git merge => Branchleri ana branch ile birleştirmek için kullanılır.Başka bir branch'da olan değişiklikleri, bulunduğumuz branch ile birleştirmek istediğimizde kullanılır.
#### git switch => İstediğimiz branch geçiş yapmak için kullanılır.
#### git stash => Üzerinde çalıştığımız ancak henüz commit etmediğimiz değişikliklerin geçiçi olarak git tarafından saklanması için kullanılır.
#### git stash pop => Saklanan dosyayı geri getirir.
#### git restore => Yapılan commit'i silip bir önceki commit'e geri dönmek amacıyla kullanılır.
#### git checkout => Dosyadaki değişiklikleri geri alıp son commit edilmiş haline geri döndürür ve istediğimiz commit'e gitmemizi sağlar.Branch’ler arası veya commit'ler arası geçiş yapmak istediğimizde kullanılır.
#### git diff => Git'de iki versiyon, commit arasındaki farkları görmek için kullanılr.Repository üzerinde yapılan değişikliklerden sonra dosyalar arasında oluşan farklılıkları göterir.
#### git reset => İstadiğimiz commit'e geri götürür ve diğer(geldiğimiz) commitleri siler.
#### git reset hard => Tüm dosyalarda yaptığımız değişiklikleri geri alır.
#### git clone => Mevcut bir Remote Repository'de bulunan dosyaların bilgisayarımızda bir kopyasının oluşturulmasını sağlar.
#### git push => Projemizde aldığımız commit'leri, remote repository'e gönderir.


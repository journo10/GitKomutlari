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

#### git config --global user.name "AD"
#### git config --glabal user.email "EMAİL"
#### Adı gösterir => git config user.name
#### Email gösterir => git config user.email
#### git status => Git'in güncel durumunu gösterir.
#### git init => Git'e bağlamak, git'i klasörde aktif etmek için ve içerisinde kullanılabilecek bir yazılı, çizili vs belgeyi takip etmek için kullanılır.
#### git add . => Dosyaları dizine ekler ve commitlemeye hazır hale getirir. Mevcut dizindeki tüm dosyaları dizine ekler.
#### git commit -m "Mesaj" => Git'e eklediğimiz dosyaları kalıcı olarak git veri tabanına işler.
#### git log => İşlem yapılan commitleri gösterir.
#### gitignore => Bazı uzantı veya dizindeki dosyaların git'e gönderilmesini engellemek oluşturulur, uzantı dosyasını içine yazarak uygulanır.
#### git branch => Yeni bir branch açmak için kullanılır.
#### git merge => Branchleri ana branch ile birleştirmek için kullanılır.
#### git switch => İstediğimiz branch geçiş yapmak için kullanılır.
#### git stash => Üzerinde çalıştığımız ancak henüz commit etmediğimiz değişikliklerin geçiçi olarak git tarafından saklanması için kullanılır.
#### git stash pop => Saklanan dosyayı geri getirir.
#### git restore => Yapılan commit'i silip bir önceki commit'e geri dönmek amacıyla kullanılır.
#### git checkout => Dosyadaki değişiklikleri geri alıp son commit edilmiş haline geri döndürür ve istediğimiz commit'e gitmemizi sağlar.
#### git diff => Git'de iki versiyon, commit arasındaki farkları görmek için kullanılr.
#### git reset => İstadiğimiz commit'e geri götürür ve diğer(geldiğimiz) commitleri siler.
#### git reset hard => Tüm dosyalarda yaptığımız değişiklikleri geri alır.



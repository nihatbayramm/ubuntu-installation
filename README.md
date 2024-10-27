( Ubuntu kurulumundan sonra terminalde işinize yarayacak komutları https://aktif.net/linux-komutlari/ sitesinden ulaşabilirsiniz . )

İhtiyacınız olacaklar:

*4 GB veya daha büyük bir USB bellek/flaş sürücü
*Microsoft Windows XP veya üzeri
*Rufus  ya da ücretsiz ve açık kaynaklı bir USB bellek yazma aracı
*Bir Ubuntu ISO dosyası. İndirme bağlantıları için Ubuntu'yu edinin'e bakın : https://ubuntu.com/download


1. Ubuntu ISO Dosyasını İndirin
Açıklama: Ubuntu'nun resmi web sitesinden (ubuntu.com) ihtiyacınıza göre Ubuntu Desktop veya Ubuntu Server ISO dosyasını indirin. Masaüstü sürümü, günlük kullanıcılar için önerilirken, server sürümü sunucular için kullanılır.
resimler :

![Screenshot from 2024-10-26 12-55-52](https://github.com/user-attachments/assets/27955a33-8b33-4383-85b1-d0959ff40a49)

2. USB Belleğe Yazdırma Programını İndirin (Rufus veya Etcher)
Açıklama: İndirdiğiniz ISO dosyasını bir USB belleğe yazdırmak için bir yazılım (örneğin, Rufus veya Etcher) indirin. Bu yazılımlar, ISO dosyasını USB'ye boot edilebilir şekilde aktarmanıza yardımcı olur.

*rufus resimleri :
1. Adım: Rufus programını açın:
![rufus1](https://github.com/user-attachments/assets/430b5dff-f505-4dcf-ad3e-a1fd71958b91)
*Rufus programını çalıştırdıktan sonra USB belleğinizi bilgisayara takın. Sonrasında en yukarıda bulunan “Aygıt” sekmesinden taktığınız USB belleği seçin.

2.adım : Yazdırmak istediğiniz ISO dosyasını seçin :
![rufus2](https://github.com/user-attachments/assets/79824c6e-0415-419d-8e46-cd9cf6022681)
*Bu adım için ISO dosyasını hazırlık kısmında belirttiğimiz gibi bilgisayarınıza indirmiş olmanız gerekiyor. Şimdi, indirdiğiniz ISO dosyasını sağ yukarı tarafta bulunan “SEÇ” butonuna tıklayarak seçin. “Önyükleme seçimi” kısmında yüklediğiniz dosyanın isminin göründüğüne emin olun.

3.adım : Dosya sağlamlığını kontrol edin:         
![image](https://github.com/user-attachments/assets/8e277877-77bd-4def-9023-40d5eb7a32a8)
*Bazı durumlarda indirmiş olduğunuz ISO dosyasında hasarlar meydana gelmiş olabilir. Böyle bir durum olmadığından emin olmanız en doğrusu. Çünkü işlemi başlattıktan belli bir süre sonra hasarlı dosya kullandığınızı öğrenmek can sıkıcı olabilir

4.adım : USB bellek yazdırma işlemini başlatın:

![image](https://github.com/user-attachments/assets/382b1a49-4023-4e19-b477-5c854c9da84c)
*ISO dosyanızın sağlamlığını da kontrol ettiğinize göre, artık işlemi başlatmak için önünüzde bir engel bulunmuyor. Bunu da en altta bulunan “BAŞLAT” butonuna basarak yapabilirsiniz. Ancak bu butona bastıktan sonra karşınıza bir uyarı penceresi çıkacak:

![image](https://github.com/user-attachments/assets/79abf057-86fa-44fb-8f45-19b4818d6b81)
*Rufus’un Ubuntu’yu yüklemek için ihtiyacı olan bir takım dosyalar var. Karşınıza çıkan kutucukta “Evet” tuşuna basmanız dahilinde, bu dosyalar Rufus’un bulunduğu dizine indirilecek ve program tarafından otomatik olarak kullanılacak. Bu işlem sonrasında bir kutucuk daha gelecek:


![image](https://github.com/user-attachments/assets/a933da9a-6c74-479e-9be2-17c1291ba122)
*Bu kutucukta, seçtiğiniz ISO dosyasının iki farklı şekilde yazılması mümkün olduğu için hangisini seçmek istediğiniz soruluyor. Rufus’un önerisine uyun, “ISO Yansıması modunda yazdır” kutucuğunu işaretleyin ve “OK” tuşuna basın. Şimdi sıra geldi işleme geçmeden önceki son kutucuğa:


![image](https://github.com/user-attachments/assets/ca9bf710-c7f1-40d3-a103-c88dc5fe6a9b)
*Eğer USB belleğinizde yedeklemeniz gereken bir dosya bulunmuyorsa, bu pencerede “Tamam”a basarak ilerleyebilirsiniz. Çünkü bu işlem sonrası USB belleğinizde bulunan bütün veriler silinmiş olacak. Yerine de Ubuntu kurulum dosyaları getirilecek.

5. Adım: Ubuntu kurulum USB belleğiniz hazırlandı:
![image](https://github.com/user-attachments/assets/75d7694c-d249-4431-8ddf-9d25290ee734)
*Eğer yukarıda verdiğimiz adımları yerine getirdiyseniz, Ubuntu kurulumu için kullanacağınız USB belleğinizin yazdırma işlemi başarıyla bitmiş olmalı. İşlemin bitip bitmediğini yine “Durum” sekmesinde bulunan kutucuğa bakarak anlayabilirsiniz. “HAZIR” yazıyorsa, işlem tamam demektir.


************** BİOS AYARLARI ***************

USB Flash Sürücüden Önyükleme Yapın
Doğal önyüklenebilir bir USB flash sürücü veya DVD oluşturduktan sonra, kurulum medyası hala içindeyken bilgisayarınızı yeniden başlatın. Ubuntu kurulum penceresi otomatik olarak görünmezse, bilgisayarınızı yeniden başlatın ve BIOS'a girin. Bilgisayarınız, BIOS'a girmek için hangi tuşa basmanız gerektiğini söyleyecektir. Çoğu bilgisayar için, F12'ye basmak işe yarar. Diğer bilgisayarlarda, F2, F10, Esc veya Del olabilir.

Şimdi, Önyükleme Sırası'na gidin ve birincil önyükleme aygıtı olarak USB Depolama Aygıtı'nı veya DVD kullanıyorsanız DVD sürücüsünü seçin. BIOS menüsü flash sürücünüzü birden fazla kez listeliyorsa, kural ilk bahsedilen veya listelemeyi seçmektir. Benzer şekilde, birden fazla UEFI listesi varsa, her zaman USB flash sürücünüzün adıyla ilk UEFI listesini seçin.

USB flash sürücünüzü menüde hiç bulamıyorsanız, BIOS Kurulumu > Gelişmiş Önyükleme Seçenekleri > Eski Seçenek ROM'larını Etkinleştir > Uygula'yı seçin . UEFI önyükleme modundayken, bu Eski Seçenek ROM'larının yüklenmesine izin verecektir.

**************** KURULUM ****************
1.ADIM : Ubuntu'yu yükleyin
**Bir sonraki ekranda Ubuntu'yu deneme veya kurma seçeneğiniz olacak.
Ubuntu'yu deneyin
"Ubuntu'yu Dene" seçeneğini seçmek bilgisayarınızda kalıcı bir değişiklik yapmaz. Ubuntu'yu kullanma konusunda hala kararsızsanız veya sınırlı sistem kaynaklarınız varsa bu idealdir. Bu yolu izlerseniz, Install Ubuntu'ya tıklayarak doğrudan test ana sayfasından kurulumu daha sonra tamamlama seçeneğiniz olacaktır .

**Ubuntu'yu kurun
Ubuntu'yu yüklemek, bilgisayarınızdaki veya ayrılmış bölümdeki diğer işletim sistemlerini üzerine yazacaktır. Bu, ayarlar, belgeler, dosyalar, fotoğraflar ve videolar dahil olmak üzere tüm verilerinizi silecektir. Verilerinizi önceden yedeklediğinizden emin olun! Şimdi Ubuntu'yu Yükle'ye tıklayın .
Dilinizi seçin; varsayılan olarak İngilizce (ABD) olarak ayarlanmıştır. Sonra, klavye düzeninizi seçin ve Devam'a tıklayın .

![KUR](https://github.com/user-attachments/assets/fa28f45d-7749-4ddc-a0aa-da3d2c1ad1ef)

2.ADIM : İnternete bağlanın
Kablosuz bir ağa bağlanıp bağlanmamayı seçebilirsiniz, ancak bunu yapmanızı öneririz. İnternet bağlantısı, üçüncü taraf yazılımları yüklemenize, güncellemeleri indirmenize, saat diliminizi otomatik olarak algılamanıza ve diliniz için tam destek yüklemenize olanak tanır. Bu şekilde, hemen işe koyulabilirsiniz.

![kur2](https://github.com/user-attachments/assets/f1174853-b16f-463c-845e-cb073c03b044)

3.ADIM : Kurulum Kurulumu
güncellemeleri ve diğer yazılımları yüklemeniz istenecektir. İki seçenek mevcuttur: normal ve minimal. Normal kurulum bir web tarayıcısı, yardımcı programlar, ofis yazılımları, oyunlar ve medya oynatıcılarla birlikte gelir. Minimal kurulum bir web tarayıcısı ve temel yardımcı programlarla birlikte gelir ve hafif kullanıcılar veya daha küçük sabit disklere sahip olanlar için idealdir.

![KUR3](https://github.com/user-attachments/assets/242cab31-a624-42f4-ab0f-2d64019d656a)
Diğer seçenekler altında , Ubuntu'yu yüklerken güncellemeleri indir seçeneğinin işaretli bırakılmasını öneririz . Bu, ilk kurulumu yavaşlatır ancak daha sonra güncellemeleri manuel olarak yüklemek zorunda kalmaktan kurtarır. Ayrıca en iyi deneyim için Grafikler ve Wi-Fi donanımı ve ek medya biçimleri için üçüncü taraf yazılımları yükle seçeneğini işaretleyin . Ardından Devam'a tıklayın .

4.ADIM : Kurulum Türü
Sonraki ekran Ubuntu'yu nasıl kurmak istediğinize karar vermenizi sağlar. Ubuntu'nun tek işletim sistemi olmasını istiyorsanız, Erase disk and install Ubuntu'yu seçin. Bu, tüm işletim sistemlerindeki tüm programlarınızı, belgelerinizi, fotoğraflarınızı, müziklerinizi ve dosyalarınızı siler. Bu kılavuz için, Erase disk and install Ubuntu'yu seçeceğiz .

Mevcut işletim sisteminizin yanına Ubuntu'yu kurmak istiyorsanız Başka Bir Şey'i seçin . Bu seçenek, bölümleri kendiniz oluşturmanıza veya yeniden boyutlandırmanıza ya da Ubuntu için birden fazla bölüm seçmenize olanak tanır. Bu yolu seçiyorsanız, Ubuntu'yu kurmak istediğiniz bölümü seçin veya Yeni Bölüm Tablosu... öğesine tıklayın.

![KUR01](https://github.com/user-attachments/assets/ae88df20-fa14-4592-8c08-1765a9103e67)

**Bu, bilgisayarınızda yeni bir bölüm tablosu oluşturacak ve diğer tüm bölümleri değiştirecektir. İsterseniz bunu daha sonra geri alabilirsiniz. Ardından Devam'a tıklayın . Seçiminizi yapın ve Şimdi Yükle'ye , ardından Devam'a tıklayın . Uyarı bilgilerini inceleyin ve Devam'a tıklayın .

6.ADIM : Konum, Saat Dilimi ve Kişisel Bilgi Ayarları
Şimdi konumunuzu seçin ve saat diliminizi ayarlayın. İnternete bağlıysanız, Ubuntu konumunuzu ve saat diliminizi otomatik olarak algılayacağı için bu adım gerekli olmayacaktır. Yanlış yaparsa, konum metin kutusuna konumunuzu yazarak girişi düzenleyin ve Devam'a tıklayın .

![KUR06](https://github.com/user-attachments/assets/a2e454fb-0142-41b0-b8d6-75fe286b2b57)

7.ADIM : Who are you ekranında adınızı ve bilgisayarınızın adını girin, otomatik olarak bir kullanıcı adı oluşturulacaktır. Bunları daha sonra her zaman değiştirebilirsiniz. Ardından şifrenizi seçin ve onaylayın.

![kurrr44](https://github.com/user-attachments/assets/4a87369b-2a0d-4db9-aa60-f93317cfa980)

****Şimdi, otomatik olarak mı yoksa parola ile mi oturum açmak istediğinizi seçin. İkincisini seçerseniz, Ubuntu her oturum açmak istediğinizde veya Terminal'de belirli görevleri gerçekleştirmek istediğinizde parolayı isteyecektir. Ayrıca Active Directory'yi kullanma seçeneği de vardır.

Arkanıza yaslanın ve kurulumun tamamlanmasını bekleyin. Bu arada, Ubuntu'dan ne bekleyebileceğinizi anlamak için açılış ekranındaki Ubuntu slayt gösterisini izleyebilir veya kaydırabilirsiniz. Kurulum tamamlandıktan sonra, kurulum medyasını çıkarın ve Enter tuşuna basın .


8.ADIM : Ubuntu'yu güncelleyin
En son özelliklere, güvenlik yamalarına ve yazılım güncellemelerine sahip olduğunuzdan emin olmak için kurulumdan sonra Ubuntu'yu güncellemeyi denemek her zaman iyi bir fikirdir. Ubuntu'yu güncellemenin iki yolu vardır: Yazılım Güncelleyici uygulaması veya Terminal aracılığıyla.

Yazılım Güncelleyici ile Ubuntu'yu güncelleyin
Ubuntu'yu Yazılım Güncelleyici aracılığıyla güncellemek için, ya Ara'ya tıklayıp " Güncelle" yazabilir ya da uygulama menüsüne (ekranınızın sol alt köşesindeki dokuz küçük kareden oluşan simge) tıklayıp Yazılım Güncelleyici'yi arayıp tıklayabilir , ardından Şimdi yükle'ye tıklayabilirsiniz . Ayrıca daha sonra size hatırlatmasını da isteyebilirsiniz.

---Ubuntu'yu Terminal aracılığıyla güncelleyin---
Terminal, komut istemi veya kabuk, Ubuntu'nun yerel komut satırı aracıdır. Ubuntu'yu Terminal aracılığıyla nasıl güncelleyeceğiniz aşağıda açıklanmıştır. Ctrl+Alt+T tuşlarına basın veya uygulama menüsüne tıklayın ve Terminal'i seçin, ardından aşağıdaki komutları yazın ve sırayla Enter'a basın:

sudo apt-get update

sudo apt-get upgrade

sudo reboot

--Bu işlemin, yüklenebilecek güncelleştirme sayısına bağlı olarak birkaç dakika sürebileceğini, özellikle de kurulum sırasında minimum yükleme seçeneğini seçtiyseniz, unutmayın.

***** 9.ADIM : Ubuntu'yu Kullanmaya Başlayın ******
Tebrikler! Artık Ubuntu'yu çeşitli görevler için kullanmaya başlamaya hazırsınız. Örneğin, DOC, DOCX, XLS, XLSX, PPT ve PPTX dosyalarıyla uyumlu popüler bir tam ofis paketi olan LibreOffice ile belgeler oluşturabilir ve düzenleyebilirsiniz. Ubuntu deneyiminizi renklendirebilecek diğer popüler uygulamalar arasında WPS Office, VLC Media Player, GIMP, Steam, Kdenlive, Krita, VirtualBox, Google Chrome/Firefox/Brave, Scribus, OpenShot, Geary, Atom ve Darktable bulunur.

--> Bu kapsamlı kılavuzda, minimum sistem gereksinimlerini anlamaktan başlayarak, gerçek kuruluma ve son olarak sistemi güncellemeye kadar Ubuntu'yu bir Windows cihazına yüklemenin ayrıntılı sürecini size anlattık. Bu adımları izleyerek, artık Ubuntu'nun açık kaynaklı yeteneklerinin ve çok sayıda önceden yüklenmiş uygulamasının keyfini çıkarabilir ve size sağlam ve kullanıcı dostu bir işletim sistemi deneyimi sunabilirsiniz. <---


















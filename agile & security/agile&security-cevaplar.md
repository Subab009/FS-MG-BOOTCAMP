## Agile & Security Cevaplar
SORU 1
Öncelikle aralarıdaki farkları açıklayalım. Encode işlemi bir verinin farklı sistemler arasında dolaşabilmesi için farklı formatlara dönüştürmedir. Bu işlem gizlilik için kullanılmaz Bu yüzdende username ve password bu yöntemle saklanması mantıklı olmaz. Hashing işlemi ise doğrulama işlemidir. Veri tabanındaki bir verinin değişip değişmediğini kontrol amaçlı kullanılır. Ayrıca bir passwordun veritabanında açık bir şekilde tutulmasını engellemek ve başkaları tarafından bilinmesini istemiyorsak kullanırız. Encription bir verinin sadece gizli anahtarını bilen kişilerce okunabilmesi için gerçekleştirlen yöntemdir. Encode dan farkı sadece şifreyi bilen kişiler tarafından orjinale dönfürülebilmesidir. Hangi yöntemi kullanıcağımıza gelirsek, bence Hashing kullanmalıyız. Şöyle, elimizdeki verileri salt ile hashlayıp saklamak olabilecek saldırılara karşı diğer yöntemlere nazaran daha fazla koruma sağlayacaktır.

SORU 2
Öncelikle bu kişi grubun en tecrübelisi ise ona saygılı davranırım. Ona IDOR zafiyeti hatası hakkında sorular sormaya başlar kendi hatasının cevaplarını vermesini sağlarım. Sonrada onun yazdığı kodu göstererek övmeye başlarım. Ardından IDOR zafiyeti olan yere geldiğimde bir duraksar yanlış bir şey yapmış gibi davranıp hatayı görmesini sağlarım. Daha sonra hatayı kontrol edip düzeltmesini isterim.

 SORU 3
 Scrum başarılı agile metodlarındandır. Karmaşık yazılım projelerinin başarı oranını yükseltmek için oluşturulmuştur ve en yaygın kullanılan proje yönetim metotlarından biridir. Scrum metodunun önemli 3 ilkesi vardır: Şeffaflık, Denetleme, Adaptasyon. Şeffaflık ilkesi şunu ön plana çıkartır: Proje gizli kapaklı ilerletilmek yerine projenin her adımının ilgili kişiler tarafında takip edilmesi. Denetlemede ise belli aralıklarda projedeki gelişmeler ilgili kişilere sunulur ve sonuçlar değerlendirilir. Adaptasyonda ise proje anlaşmadaki kurallara göre değilde gelen değişiklik taleplerine göre devam etmelidir. Bir scrum takımında 3 tane rol bulunur. Bunlar Scrum Master, Product Owner ve Development Team. Scrum Master roldeki kişiler scrum kurallarını iyi bilen kişiler olmalıdır. Scrum master rolündeki kişileri bisikletteki destek tekerlerkleri gibi düşünebiliriz. Scrum takımındaki kişilerin scrum metodolojisine uygun hareket etmeleri için kişilere yardımcı olmak scrum master rolündeki kişinin görevidir. Ürün sahibi tek başına kararlar alan ve geliştirme takımına bunları dayatma gücüne sahip olan kişi değildir. Bu roldeki kişilerin görevleri geliştirme takımı ile paydaşlar (stakeholders) arasındaki iletişimi sağlamaktır. Ürün sahibi rolündeki kişi, paydaşlardan alınan geri bildirim ve talepler doğrultusunda ürün üzerinde ne gibi geliştirmelerin yapılması gerektiğini belirler ve bu kararları önceliklendirir. Önceliklendirilmiş kararlar doğrultusunda geliştirmeleri iş parçaları haline getirir ve geliştirme takımına iletir. Development Team ürünü oluşturan kişilerin oluşturduğu ekiptir. Takım kendi kendine hareket eder, yani otonomdur. Bu sebeple yönetici (manager) rolünde birine ihtiyaç duyulmaz. Bunun yanı sıra ekip üyeleri birbirlerinden farklı alanlarda uzmanlaşmış olabilirler. Buna karşın yine de tek bir işle meşgul olmazlar, çapraz görev dağılımı yapabilmelidirler. Böylece ürün hakkındaki bilgiler tek bir kişide birikmez, ekip içerisine yayılır. Scrum toplantılarına Sprint denir. Bu toplantılar 1-4 hafta süreler arasında planlanır. Bu süreyi ekip belirler.Sprint Planlama: Sprint, planlama toplantısı ile başlar. Scrum master, geliştirme ekibi ve ürün sahibinin katılımı ile bu toplantı gerçekleştirilmektedir. Planlama toplantılarının amacı, ürün için talep edilen geliştirmelerin yer aldığı ürün iş listesi içerisindeki işlerden bir kısmının geliştirme ekibi ile paylaşılmasıdır. Bu toplantının sonunda aktif sprint içerisinde yapılmasına karar verilen işler, ürün iş listesinden sprint iş listesine alınır.Günlük Scrum Toplantısı: Günlük toplantılarda geliştirme takımında yer alan kişiler dün neler yaptıklarını, bugün neler yapacaklarını anlatırlar. Bunları anlatmalarının amacı hesap vermek değil, takım arkadaşları ile bilgi paylaşmaktır. Üstlenilen görevlerin tamamlanması konusunda bloklanılan, yardım beklenen bir konu varsa bu toplantıda belirtilir.Sprint Değerlendirme:Scrum takımı üyeleri ve önemli paydaşların katılımı ile bu toplantı yapılmaktadır. Bu toplantının amacı sprint süresince geliştirmesi tamamlanmış ve ürünün bir parçası haline gelmiş özelliklerin tanıtılmasıdır. Bir nevi ürünün reklamını yapmak da diyebiliriz. Paydaşlardan geri bildirimler alınır ve gerekiyorsa ürün üzerinde revizyonlar yapılır.Sprint Retrospektif:Scrum takımının tamamının katılımı ile yapılan toplantıdır. Sprint sürecinin takım olarak değelendirilmesi amacıyla düzenlenir. Nelerin daha iyi yapılabileceği veya nelerin iyi yapıldığı konuları üzerine konuşulur. Ekip arkadaşları birbirlerine geri bildirimler verir ve bu sayede daha iyi işleyen bir ekibin oluşması amaçlanır.Ürün İş Listesi Düzenleme:Scrum takımındaki bireylerin katılımı ile yapılmaktadır. Toplantının amacı ürün iş listesinin düzenlenmesi ve işlerin detaylandırılmasıdır. Bu toplantı içerisinde sorulan sorular bir sonraki sprint planlama toplantısına kadar cevaplanmalı ve bu şekilde işler netleştirilmelidir.
 
SORU 4
Repository: Proje dosyalarını uzak bir sunucuda depolar. Genel kullanımda “Repo” olarak da kısaltılır.
Branch: Projenin bir çok bölümünü derli toplu şekilde tutulmasını sağlar.
Commit: Proje dosyalarınızda belli bir değişiklik yaptığınızda o değişikliğin anlık görüntüsünün alınıp kaydedilmesine denir.
Pull: Fork edilen proje üzerinde değişiklikler yaptıktan sonra gerçek repository’e gönderilerek o projenin sahibi olan geliştiricinin değerlendirmesine sunmaktır. Eğer PR kabul edilirse ana repository üzerinde, fork ettiğiniz proje üzerinde değişiklikler işlenir.
Merge: Branch üzerinde yaptığımız değişiklikleri master branch’i üzerinde birleştirme işlemidir.
Push: Remote branch üzerinde update işlemini gerçekleştirir.
Merge: Bir branch’taki değişiklikleri başka bir Branch üzerine almaktır.
Fork: Repository’nin bir kopyasını oluşturur.

SORU 5
Kısaca yapılan bir değişikliği geri almak denebilir.

SORU 6
Sql veritabanları sabit satır ve sütunlara sahip tabloları ilişkilendirerek verileri depolarken Nosql veritabanlarının birden fazla veri depolama yöntemi vardır. Bunlar doküman oluşturma, anahtar-değer çiftleri oluşturma, dinamik sütun ve satıra sahip tablolar oluşturma ya da grafik oluşturma şeklinde özetlenebilir. Sql veritabanları ihtiyacınız önceden belirlemenizi ister. Daha sonra ise tablolarlar ilişkilendirmeyi ister. NoSql de ise önceden bir şema oluşturmanıza gerek yoktur. İhtiyaçlarınız değiştikçe veritabanı üzerinde değişiklik yapmanız kolaydır. Şemanız dokümandan dokümana değişebilir. Büyük veri karşısında iki tip veritabanının da ölçekleme çözümleri farklıdır. Sql veritabanları dikey ölçekleme yapısına sahiptir. Yeni veri geldikçe depolama alanınızı kapasitesi daha büyük olan sunuculara taşımanız gerekmektedir ve bu durum size gittikçe pahalıya mal olmaktadır. Onun yerine, NoSql veritabanları ise yatay ölçekleme yapısına sahiptir. Yani yeni verileri farklı depolama alanlarına bölerek tutarsınız. Bu yaklaşım hem daha ucuzdur hem de verilere ulaşma konusunda size hız kazandırır.Eğer daha karmaşık sorgular yapmak istiyorsanız, ileride uygulamanızın boyutu ve veri tipleri için fazla bir değişiklik olursa Sql yok değişikler çok olucak olursa nosql seçilmeli.


SORU 8
b.Privacy Violation

SORU 9
a.Kullanıcı Adı, Cep telefonu OTP, Parmak İzi
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

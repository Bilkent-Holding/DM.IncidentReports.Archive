
Incident #0001
 
10.10.2025 09:52 

Kenan Aydugan Bey tarafından, kasa kapanışı sonrasında alınan çıktıya Onay ve Genel Müdür bilgisinin eklenmesi istenmiştir.
Uygulamanın kaynak kodu olmadığı için IIS altındaki derlenmiş resource incelenmiştir.

Bu isteğin karşılanabilmesi için ise Yaz.aspx dosyasına html içinde elle müdahale edilmiştir.
Yaz.aspx dosyasının yedeği, yine IIS altında Yaz.aspx.OriginalFile adıyla korunmuştur.

Uygulamanın assembly'sinin dnSpy ile incelenmesi ile de connection string bilgisinin aşağıdaki gibi olduğu görülmüştür.

Provider=SQLOLEDB.1;Password=+RDgb!tgh7823yh;Persist Security Info=True;User ID=sa;Initial Catalog=sports_kasa;Data Source=10.10.30.147\SPORTS

Bu gün itibariyle alınan dosyalar GitHub'daki Incident repository'sinde ilgili klasöre eklenmiştir.

Salih Murat SEZGİ


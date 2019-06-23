# Sayı Tahmin Oyunu
+/- ipuculu sayi oyunu

Geliştirilmiş olan yazılım bir bilgisayar ile kullanıcı arasında oynanan bir oyundur. Yyazılım ve kullanıcı rakamları birbirinden farklı 4 basamaklı bir sayı tutarlar. Yazılım, kullanıcının tahmin ettiği sayıyı bulmaya, kullanıcı da bilgisayarın tahmin ettiği sayıyı bulmaya çalışır. Tahminler sonucunda tutulan sayı ile ilgili ipuçları verilir. Eğer tahmin edilen sayı içinde tutulan sayının rakamlarından varsa ve basamak değeri doğruysa “+” değer olarak ipucu verilir, basamak değeri yanlış ise “-” değer ipucu olarak verilir. Örneğin bilgisayar 5483 sayısını tutsun ve kullanıcı 3468 tahmini yaptığında 4 sayısının basamak değeri doğru olduğu için +1, 3 ve 8 sayısının basamak değeri yanlış olduğu için -2 değeri dönülecektir.  

# Oynanış

1) Başla butonuyla oyuna başla.
2) Senin Sayın Bu Olabilir mi? kısmında verilen tahminde;  <br/>
Basamağı ve değeri doğru sayılar varsa o kadar + ipucu gir.<br/>
Basamağı yanlış ama değeri doğru sayılar varsa o kadar - ipucu gir.
3) İpucuları girince İpucu Tamam!'a tıkla.
4) Oyunun tuttuğu sayıyı bulmak için Senin Tahminin kısmına bir tahmin gir.
5) Hem yeni tahmin almak hem yeni tahmin vermek için Tahmit Et'e tıkla.
6) Sonraki tahmininde benzer şekilde sana verilen ipucudan yararlan.
7) Kaybettiğinde, kazandığında ya da yeniden oynamak istediğinde Tekrar Oyna butonuna tıkla.

-Kurallara oyun sırasında erişmek için ? butonuna tıklayabilirsiniz.

# Kurulum

Uygulama Visual Studio 2017'de bir C# form uygulaması olarak geliştirilmiştir. 
final_oyun/final_oyun.sln dosyasını Visual Studio ile açarak yazılımı çalıştırabilirsiniz.

Ya da projenize Form1.cs, Form1.Designer.cs ve Program.cs'i dahil ederek derleyebilirsiniz.

Ya da final_oyun/final_oyun/bin/debug/final_oyun.exe'yi açarak uygulamayı direkt çalıştırabilirsiniz.

# Kullanıcı Input Kontrolleri

Kullanıcının girdiği +/- ipuçlarının büyüklükleri toplamı 4'ü geçerse geçersiz ipucu vermiş olur ve tekrar ipucu vermesi istenir.

Bunun dışında kullanıcının ipucularını doğru vermesi beklenmektedir.
Kullanıcının aklındaki sayı 1234 ve yazılımın tahmini 1256 olduğunda kullanıcı +1,-1 gibi yanlış bir tahmin verdiğinde yazılım ilerki adımlarda çalışmayacaktır!

Kullanıcının yazılımın sayısını tahmin etmek için girdiği sayının rakamları farklı 4 basamaklı bir sayı olup olmadığı kontrol edilmektedir.
Eğer koşullara uygun bir tahmin girilmediyse başka bir tahmin girmesi istenmektedir.


# Örnek Ekran Çıktısı
<a href="https://ibb.co/K5jLhWt"><img src="https://i.ibb.co/6yR1wFK/ornek-ss.png" alt="ornek-ss" border="0"></a><br />

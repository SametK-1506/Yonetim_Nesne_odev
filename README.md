# Yonetim_Nesne_odev

## 📄 Proje Raporu (Ödev Hazırlama Yöntemi)

Projede tüm diller için ortak bir OOP mimarisi kurulmuştur. `KuantumNesnesi` soyut sınıfı (abstract class) ile temel özellikler ve kapsülleme (encapsulation) sağlanmıştır. Sadece tehlikeli maddelerin soğutulabilmesi için `IKritik` arayüzü (interface) tasarlanmış, `VeriPaketi`, `KaranlikMadde` ve `AntiMadde` sınıfları türetilerek çok biçimlilik uygulanmıştır. Oyunun bitiş koşulu olan stabilite kaybı ise özel bir hata sınıfı (`KuantumCokusuException`) ile kontrol altına alınmıştır.

## ⚙️ Nasıl Çalıştırılır?

Kodları çalıştırmadan önce terminali ilgili klasörde açtığınızdan emin olun.

1. C#
dotnet run

3. Java
javac Main.java
java Main

4. Python
python main.py

5. JavaScript
npm install prompt-sync
node app.js

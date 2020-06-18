#Veri Haberleşmesi Dönem Ödevi
Teslim tarihi: 29 Mayıs 2020

Gönderim şekli: https://github.com/nyucel/blm304 adresine öğrenci_numaranız isimli bir dizin
olarak Pull Request ile gönderilmelidir. Dosyaların içerisinde hazırlayanın adı bir yorum satırında
bulunmalıdır.

Programlama dili: Yazacağınız kodları python3 ile yazmanız gerekmektedir.

Kullanılabilecek modüller: Temel python kitaplıklarını ve scapy modülünü içe aktarıp
kullanabilirsiniz. İhtiyacınız olduğunda gerekli yeni fonksiyonları kendiniz yazıp kullanabilirsiniz.
pip benzeri paket yöneticileri ile ilave bir modül yüklemeden önce mutlaka elektronik posta ile bana
sorun.

• FTP protokolünü UDP üzerinden gerçekleştiren sunucu servisini ve istemcisini yazmanız
beklenmektedir1. Sunucu 42. portu dinlemelidir ve kimlik doğrulaması yapmasına gerek
yoktur. İstemci sunucu bağlantısı için sunucunun IP adresini yazarak bağlanabilmelidir. (20
puan) Oturum açıldıktan sonra sunucuda bu servis için ayrılmış dizindeki örnek dosyaları
listeleyebilmelidir. (20 puan) İstemci GET komutunu ve dosya adını vererek sunucudan
dosya indirebilmeli ve PUT komutu ile yerelindeki dosyayı sunucuya yükleyebilmelidir. (40
puan)

• Değerlendirme sırasında her iki yazılım birer sanal makinede çalıştırılacak ve aralarındaki
TCP bağlantısı güvenlik duvarı üzerinden kısıtlanacaktır.

• Dosya aktarımı sırasında bağlantı kesintiye uğratılarak paketlerin karşıya ulaşıp
ulaşmadığının kontrolünü yapmış olmanız beklenecektir. (20 puan)

---
layout: post
title: Ubuntu Şifresi
---
## Ubuntu şifremi unuttum 

Sık sık karşılaştığım bir sorun üzerine yazıyorum ilk bloğumu ; Şifre unutmak :)

Çeşitli sebeplerden ötürü bir türlü ısınamadığım linux platformlarının hayran olduğum 
bir çok yanı da olduğu için ara sıra kullanıyorum . Ama bazen kullanma sıklığım azalınca 
o malum olay başıma geliyor ; "Şifre unutmak" . Bu yüzden de en son olarak bu sorunu
giderme konusunda ki adımlarımı aynen aktaracağım . Ben Ubuntu 12.04 kullandığım için 
aşamalar onun üzerine olacak . 

* İlk olarak işletim sistemi seçim ekranı gelince ubuntu kurtarma kipinden giriş yapıyoruz
* Sonrasında "root" kullanıcı menüsünden devam ediyoruz 
* Sonrasında 

sırası ile 
	mount -o -rw , remount /
	passwd kullanıcı_adı
	reboot
	
komutlarının verilmesi gerekir .

NOT: "passwd kullanıcı_adı" komutunu verdikten sonra sizden sizden yeni şifreyi girmenizi
isteyecek . Siz şifreyi girerken güvenlik açısından "*" ile dahi kodlanarak gösterilmeyecek
ancak arka planda işlenecek . Siz şifrenizi yazıp "enter" yapın devam edin :) Tekrar 
yazdıktan sonra şifre değiştirme başarılı benzeri bir bilgilendirme yazacak . Son komutu da
verip yeni şifrenizin keyfini sürebilirsiniz . Sevgiyle kalın :)


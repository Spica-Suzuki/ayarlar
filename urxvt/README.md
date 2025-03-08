# Açıklamalar:

urxvt*scrolling: true
// terminalde kaydırma özelliğini açar

!URxvt.scrollWithBuffer: true (yorum satırında olduğu için etkisiz)
//Açık olduğunda terminal kaydırma yaparken ara bellekteki eski satırları saklar
//Kapalı olduğunda sadece gözüken eski satırlar saklanır
URxvt.secondaryScreen: true
//vim ve htop gibi programlar ikincil bir ekran tamponu kullanıyor.
//eğer false olursa vim kapanınca eski çıktılar ekrandan silinir 


# Kullanılan Eklenti
https://github.com/gryf/tabbedalt

# İş bittiğinde şu komutu çalıştır
xrdb -merge .Xdefault

# Açıklamalar:

urxvt*scrolling: true
// terminalde kaydırma özelliğini açar

!URxvt.scrollWithBuffer: true (yorum satırında olduğu için etkisiz)
//Açık olduğunda terminal kaydırma yaparken ara bellekteki eski satırları saklar
//Kapalı olduğunda sadece gözüken eski satırlar saklanır
URxvt.secondaryScreen: true
//vim ve htop gibi programlar ikincil bir ekran tamponu kullanıyor.
//eğer false olursa vim kapanınca eski çıktılar ekrandan silinir

! urxvt*saveLines: 1000
//Açık olduğunda  son bin satırın 

! urxvt*lines: 30
! urxvt*geometry: 120x4


//Urxvt fontları:

URxvt*faceName: Hack
URxvt*font: xft:Hack:size=12
URxvt*faceSize: 12
URxvt*boldFont: xft:Hack:bold:size=12
URxvt*italicFont: xft:Hack:italic:size=12
URxvt*boldItalicFont: xft:Hack:bold:italic:size=12
// İki türlü font var. xft ve bitmap.
// URxvt.font bitmap fontlar içindir, x11'in eski font sistemini kullanır. xft (xfreetype) desteklemez
// URxvt*font ise xft desteklidir, daha iyi ve moderndir

URxvt.iso14755: false
URxvt.iso14755_52: false
// iso standartlarını devre dışı bırakmak sade, uyumlu ve performanslı olur.
// ancak bazı eski x11 protokollerini kırabilir.



# Kullanılan Eklenti
https://github.com/gryf/tabbedalt

# İş bittiğinde şu komutu çalıştır
xrdb -merge .Xdefault

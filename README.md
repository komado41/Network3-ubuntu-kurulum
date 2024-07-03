# Network3-ubuntu-kurulum
oncelikle dosyayi sunucumuza indiriyoruz 
---console
wget https://network3.io/ubuntu-node-v1.1.tar
---
dosyayi cikaralim 
tar -xf ubuntu-node-v1.1.tar
dizine gecis yapalim
cd ubuntu-node
nodu baslatalim 
sudo bash manager.sh up
node is ready mesajini gorduk mu tamamdir
simdi panelden kontrol edelim puanimizi tarayimiza asagidaki kodu duzenleyip yapistiralim
https://account.network3.ai/main?o=sunucu-ip:8080
E-postanızı bağlamak isterseniz, önce e-postanızla panele  giriş yapın. Sonra kontrol panelinde current node yazan yerde  '+' düğmesine tıklayın. Açılan  kutuya nodun özel anahtarını girebilirsiniz. Nodu bağlamak için özel anahtarı şu komutla alabilirsiniz:
sudo bash manager.sh key

# Grafik İncelemesi
Korelasyon Matrisi
Grafik, belirli ağlar için korelasyon matrisini göstermektedir. Korelasyon matrisi, iki değişkenin birlikte nasıl değiştiğini ölçen bir matristir. Renk ölçeği, bu korelasyon değerlerinin pozitif veya negatif olduğunu ve derecesini gösterir.

### Sütun İsimleri ve Grafiklerdeki İsimler
network-node-hemi: Bu sütun ve grafik başlıkları, her bir verinin hangi ağa (network), hangi düğüme (node) ve hangi yarıküreye (hemi) ait olduğunu belirtir.
network: Ağ numarasını gösterir. Örneğin, "1-1-rh" ifadesi, 1 numaralı ağdaki 1 numaralı düğümün sağ yarıkürede (right hemisphere, rh) olduğunu belirtir.
node: Her bir ağ içindeki belirli düğümleri ifade eder.
hemi: Bu, yarıküreyi belirtir; "lh" sol yarıküreyi (left hemisphere), "rh" sağ yarıküreyi (right hemisphere) ifade eder.
Grafiğin Yorumlanması
### Renk Skalası:

Kırmızı tonları: Pozitif korelasyonu (1'e yakın değerler) gösterir, yani iki değişken birlikte artar veya azalır.
Mavi tonları: Negatif korelasyonu (-1'e yakın değerler) gösterir, yani bir değişken artarken diğeri azalır.
Beyaz/nötr renkler: Çok az veya hiç korelasyon olmadığını (0'a yakın değerler) gösterir.
Dendrogram: Grafiğin üst kısmındaki dendrogram, benzerliklere göre gruplandırılan ağ düğümlerini gösterir. Birbirine yakın olan düğümler, yüksek korelasyonlu olduklarını belirtir.

### Korelasyonlar:

Ana diagonal çizgi, her bir ağ düğümünün kendisiyle olan mükemmel korelasyonunu (1) gösterir.
Diğer hücrelerdeki renkler, ağ düğümleri arasındaki ilişkileri gösterir. Kırmızı hücreler güçlü pozitif korelasyonu, mavi hücreler ise güçlü negatif korelasyonu gösterir.
Grafikte, belirli ağlar arasında güçlü pozitif ve negatif korelasyonlar olduğu görülüyor. Örneğin, belirli ağların birbirleriyle çok güçlü bir pozitif korelasyona sahip olduğunu (kırmızı hücreler) ve bazı ağların birbirleriyle güçlü negatif korelasyona sahip olduğunu (mavi hücreler) görebiliriz.

### Model Sonuçları
Grafiğin üst kısmında "Model Mean Squared Error: 948.0048551358155" ifadesi yer alıyor. Bu, modelin ortalama karesel hatasının yaklaşık 948 olduğunu gösterir. Bu değer, modelin tahminlerinin gerçek değerlerden ne kadar sapma gösterdiğinin bir ölçüsüdür. Düşük bir MSE, daha iyi bir model performansını gösterir. Bu değer, modelin doğruluğunu ve tahmin yeteneğini değerlendirmek için kullanılır.

### Özet
Bu grafik, belirli ağ düğümleri arasındaki korelasyonları ve bu korelasyonların şiddetini görselleştirir. Aynı zamanda, ağların benzerliklerini gösteren dendrogramları içerir ve bu grafikteki korelasyonlar, modelin verileri nasıl kullandığını ve hangi ağların birbirleriyle daha fazla ilişkili olduğunu anlamamıza yardımcı olur.

## Katkıda Bulunma
Bu projeye katkıda bulunmak isterseniz, lütfen bir pull request gönderin veya bir sorun açın. Her türlü katkı ve geri bildirim memnuniyetle karşılanacaktır!

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakabilirsiniz.

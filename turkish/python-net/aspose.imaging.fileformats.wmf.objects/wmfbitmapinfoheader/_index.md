---
title: "WmfBitmapInfoHeader Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | WmfBitmapInfoHeader sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [static] | int | r | Yapı boyutu |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | Her pikselin formatını ve DIB'deki maksimum renk sayısını tanımlayan 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>                Bu değer<br/>                [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) Sıralamasında (bölüm 2.1.1.3) bulunmalıdır. |
| color_important | int | r/w | Görüntüleme için gerekli renk indekslerinin sayısını tanımlayan 32 bit işaretsiz tamsayıyı alır veya ayarlar<br/>                DIB.<br/>                Bu değer sıfır ise, tüm renk indeksleri gereklidir |
| color_used | int | r/w | 32 bit işaretsiz tamsayıyı alır veya ayarlar; bu değer DIB tarafından kullanılan renk tablosundaki indeks sayısını belirtir, şu şekilde:<br/>                Eğer bu değer sıfır ise, DIB BitCount değerine karşılık gelen maksimum renk sayısını kullanır.<br/>                Eğer bu değer sıfırdan farklı ve BitCount değeri 16'dan küçükse, bu değer DIB tarafından kullanılan renk sayısını belirtir.<br/>                Eğer bu değer sıfırdan farklı ve BitCount değeri 16 veya daha büyükse, bu değer sistem paletinin performansını optimize etmek için kullanılan renk tablosunun boyutunu belirtir.<br/>                Not: Bu değer sıfırdan farklı ve BitCount değerine göre renk tablosunun mümkün olan maksimum boyutundan büyükse, maksimum renk tablosu boyutu KABUL edilmelidir. |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | 32 bit işaretsiz tamsayıyı alır veya ayarlar; bu değer DIB'in sıkıştırma modunu tanımlar. Bu değer<br/>                Sıkıştırma Sıralaması (bölüm 2.1.1.7) içinde OLMALIDIR.<br/>                Bu değer, DIB bir üstten aşağıya bitmap ise, Yükseklik değeriyle gösterildiği gibi, sıkıştırılmış bir format belirtmemelidir. |
| header_size | int | r/w | Bu nesnenin boyutunu bayt cinsinden tanımlayan 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>                 |
| height | int | r/w | 32 bit işaretli tamsayıyı alır veya ayarlar; bu değer DIB'in yüksekliğini piksel cinsinden tanımlar. Bu değer SIFIR OLMAMALIDIR.<br/>                Değer pozitif ise, DIB alttan üste bir bitmap'tir ve kökeni sol-alt köşededir.<br/>                Değer negatif ise, DIB üstten aşağıya bir bitmap'tir ve kökeni sol-üst köşededir. Üstten aşağıya bitmap'ler<br/>                sıkıştırmayı desteklemez.<br/>                Bu alan, sıkıştırma değeri JPEG veya PNG formatını belirtiyorsa, sıkıştırılmamış görüntü dosyasının yüksekliğini BELİRTMELİDİR. |
| image_size | int | r/w | 32 bit işaretsiz tamsayıyı alır veya ayarlar; bu değer görüntünün bayt cinsinden boyutunu tanımlar.<br/>                Eğer Sıkıştırma değeri BI_RGB ise, bu değer SIFIR OLMALI ve YOK SAYILMALIDIR.<br/>                Eğer Sıkıştırma değeri BI_JPEG veya BI_PNG ise, bu değer sırasıyla JPEG veya PNG görüntü tamponunun boyutunu BELİRTMELİDİR. |
| planes | int | r/w | Hedef cihaz için<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) sayısını tanımlayan 16-bit işaretsiz tam sayıyı alır veya ayarlar. Bu değer<br/>                0x0001 olmalıdır. |
| width | int | r/w | 32 bit işaretli tamsayıyı alır veya ayarlar; bu değer DIB'in genişliğini piksel cinsinden tanımlar. Bu değer POZITIF OLMALIDIR.<br/>                Bu alan, sıkıştırma değeri JPEG veya PNG formatını belirtiyorsa, sıkıştırılmamış görüntü dosyasının genişliğini BELİRTMELİDİR. |
| x_pels_per_meter | int | r/w | 32 bit işaretli tamsayıyı alır veya ayarlar; bu değer DIB için hedef cihazın yatay çözünürlüğünü, piksel/metre cinsinden tanımlar<br/>                 |
| y_pels_per_meter | int | r/w | 32 bit işaretli tamsayıyı alır veya ayarlar; bu değer DIB için hedef cihazın dikey çözünürlüğünü, piksel/metre cinsinden tanımlar<br/>                 |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

WmfBitmapInfoHeader sınıfının yeni bir örneğini başlatır


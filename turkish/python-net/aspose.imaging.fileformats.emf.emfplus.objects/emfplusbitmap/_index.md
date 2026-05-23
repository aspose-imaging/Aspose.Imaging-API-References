---
title: "EmfPlusBitmap Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | EmfPlusBitmap sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | Bitmap verisini alır veya ayarlar<br/>            BitmapData (değişken): Type alanında belirtilen bitmap veri nesnesini tanımlayan değişken uzunlukta veri. Verinin içeriği ve biçimi her bitmap türü için farklı olabilir. |
| height | int | r/w | Bitmap yüksekliğini alır veya ayarlar<br/>            Height (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden yüksekliğini belirten 32-bit işaretli tamsayı.<br/>            Görüntü Type alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | Piksel biçimini alır veya ayarlar<br/>            PixelFormat (4 bayt): Bitmap görüntüsünü oluşturan piksellerin biçimini belirten 32-bit işaretsiz tamsayı. Desteklenen piksel biçimleri [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) sayım kümesinde (bölüm 2.1.1.25) belirtilir.<br/>            Görüntü Type alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR. |
| stride | int | r/w | Görüntünün stride değerini alır veya ayarlar<br/>            Stride (4 bayt): Bir tarama satırının başlangıcı ile bir sonraki satır arasındaki bayt ofsetini belirten 32-bit işaretli tamsayı. Bu değer, PixelFormat alanında belirtilen piksel başına bayt sayısı ile Width alanında belirtilen piksel genişliğinin çarpımına eşittir. Bu alanın değeri DÖRT'ün katı OLMAK ZORUNDADIR.<br/>            Görüntü Type alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | Görüntünün tipini alır veya ayarlar<br/>            Type (4 bayt): BitmapData alanındaki veri tipini belirten 32-bit işaretsiz tamsayı. Bu değer [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) sayım kümesinde (bölüm 2.1.1.2) tanımlanmış OLMAK ZORUNDADIR. |
| width | int | r/w | Görüntünün genişliğini alır veya ayarlar<br/>            Width (4 bayt): Bitmap'in kapladığı alanın piksel cinsinden genişliğini belirten 32-bit işaretli tamsayı.<br/>            Görüntü Type alanına göre sıkıştırılmışsa, bu değer tanımsızdır ve YOK SAYILMASI GEREKİR. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

EmfPlusBitmap sınıfının yeni bir örneğini başlatır


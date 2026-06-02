---
title: "WmfDeviceIndependentBitmap Sınıf"
type: docs
weight: 180
url: /tr/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---

**Summary:** The DeviceIndependentBitmap Object defines an image in<br/>                device-independent bitmap (DIB) format

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap__1) | WmfDeviceIndependentBitmap sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| a_data | System.Byte | r/w | Görüntüyü tanımlayan bir bayt dizisini alır veya ayarlar. Bu verinin boyutu ve<br/>                biçimi DIBHeaderInfo alanındaki bilgiler tarafından belirlenir. |
| cached_image | System.Byte | r/w | Önbelleğe alınmış raster görüntüyü alır veya ayarlar. |
| colors_data | System.Byte | r/w | Renk tablosunu tanımlayan isteğe bağlı bir dizi, ya RGBQuad Nesneleri (bölüm<br/>                2.2.2.20) ya da 16-bit işaretsiz tam sayılar alır veya ayarlar. Bu alanın<br/>                boyutu ve içeriği, bu DeviceIndependentBitmap'i içeren metafile kaydı<br/>                veya nesnesi ve DIBHeaderInfo alanındaki bilgilerden BELİRLENMELİDİR. Ek detaylar için ColorUsage<br/>                Enumeration (bölüm 2.1.1.6) ve BitCount Enumeration (bölüm<br/>                2.1.1.3) bakınız. |
| header | [WmfBitmapBaseHeader](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) | r/w | Görüntü hakkında bilgi belirten bir BitmapCoreHeader Nesnesi (bölüm 2.2.2.2) ya da bir<br/>                BitmapInfoHeader Nesnesi (bölüm 2.2.2.3) alır veya ayarlar. |


### Constructor: WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap__1}


```
 WmfDeviceIndependentBitmap() 
```

WmfDeviceIndependentBitmap sınıfının yeni bir örneğini başlatır.


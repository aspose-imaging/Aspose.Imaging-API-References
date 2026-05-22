---
title: "EmfPlusCompressedImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusCompressedImage nesnesi, sıkıştırılmış veri içeren bir görüntüyü belirtir."
type: docs
weight: 31
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

EmfPlusCompressedImage nesnesi, sıkıştırılmış veri içeren bir görüntüyü belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | Sıkıştırılmış görüntüyü belirten bayt dizisini alır veya ayarlar. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | Sıkıştırılmış görüntüyü belirten bayt dizisini alır veya ayarlar. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


Sıkıştırılmış görüntüyü belirten bayt dizisini alır veya ayarlar. Sıkıştırma türü veriden kendisi belirlenmelidir.

Bitmaps, EmrPlusBitmap nesneleri (bölüm 2.2.2.2) tarafından belirtilir. BitmapDataTypeCompressed, Type alanında belirtilmişse, bir EmfPlusBitmap nesnesinin BitmapData alanında bir EmfPlusCompressedImage nesnesi bulunmalıdır. Bu nesne geneldir ve aşağıdakiler dahil çeşitli sıkıştırılmış veri türleri için kullanılır: \\uf0a7 Değiştirilebilir Görüntü Dosyası (EXIF), [EXIF] içinde belirtildiği gibi; \\uf0a7 Grafik Değişim Biçimi (GIF), [GIF] içinde belirtildiği gibi; \\uf0a7 Ortak Fotoğraf Uzmanları Grubu (JPEG), [JFIF] içinde belirtildiği gibi; \\uf0a7 Taşınabilir Ağ Grafikleri (PNG), [RFC2083] ve [W3C - PNG] içinde belirtildiği gibi; ve \\uf0a7 Etiket Görüntü Dosyası (TIFF), [RFC3302] ve [TIFF] içinde belirtildiği gibi.

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


Sıkıştırılmış görüntüyü belirten bayt dizisini alır veya ayarlar. Sıkıştırma türü veriden kendisi belirlenmelidir.

Bitmaps, EmrPlusBitmap nesneleri (bölüm 2.2.2.2) tarafından belirtilir. BitmapDataTypeCompressed, Type alanında belirtilmişse, bir EmfPlusBitmap nesnesinin BitmapData alanında bir EmfPlusCompressedImage nesnesi bulunmalıdır. Bu nesne geneldir ve aşağıdakiler dahil çeşitli sıkıştırılmış veri türleri için kullanılır: \\uf0a7 Değiştirilebilir Görüntü Dosyası (EXIF), [EXIF] içinde belirtildiği gibi; \\uf0a7 Grafik Değişim Biçimi (GIF), [GIF] içinde belirtildiği gibi; \\uf0a7 Ortak Fotoğraf Uzmanları Grubu (JPEG), [JFIF] içinde belirtildiği gibi; \\uf0a7 Taşınabilir Ağ Grafikleri (PNG), [RFC2083] ve [W3C - PNG] içinde belirtildiği gibi; ve \\uf0a7 Etiket Görüntü Dosyası (TIFF), [RFC3302] ve [TIFF] içinde belirtildiği gibi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |


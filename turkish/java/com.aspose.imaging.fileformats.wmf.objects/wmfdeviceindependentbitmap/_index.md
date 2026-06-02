---
title: "WmfDeviceIndependentBitmap"
second_title: "Aspose.Imaging for Java API Referansı"
description: "DeviceIndependentBitmap Nesnesi, cihaz bağımsız bitmap (DIB) formatında bir görüntüyü tanımlar."
type: docs
weight: 27
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

DeviceIndependentBitmap Nesnesi, cihaz bağımsız bitmap (DIB) formatında bir görüntüyü tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeader()](#getHeader--) | Görüntü hakkında bilgi belirten bir BitmapCoreHeader Nesnesi (bölüm 2.2.2.2) ya da bir BitmapInfoHeader Nesnesi (bölüm 2.2.2.3) alır veya ayarlar. |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | Görüntü hakkında bilgi belirten bir BitmapCoreHeader Nesnesi (bölüm 2.2.2.2) ya da bir BitmapInfoHeader Nesnesi (bölüm 2.2.2.3) alır veya ayarlar. |
| [getColorsData()](#getColorsData--) | Renk tablosunu tanımlayan RGBQuad Nesneleri (bölüm 2.2.2.20) ya da 16 bit işaretsiz tamsayılar içeren isteğe bağlı bir dizi alır veya ayarlar. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | Renk tablosunu tanımlayan RGBQuad Nesneleri (bölüm 2.2.2.20) ya da 16 bit işaretsiz tamsayılar içeren isteğe bağlı bir dizi alır veya ayarlar. |
| [getAData()](#getAData--) | Görüntüyü tanımlayan bir bayt dizisini alır veya ayarlar. |
| [setAData(byte[] value)](#setAData-byte---) | Görüntüyü tanımlayan bir bayt dizisini alır veya ayarlar. |
| [getCachedImage()](#getCachedImage--) | Önbelleğe alınmış raster görüntüyü alır. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | Önbelleğe alınmış raster görüntüyü ayarlar. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


Görüntü hakkında bilgi belirten bir BitmapCoreHeader Nesnesi (bölüm 2.2.2.2) ya da bir BitmapInfoHeader Nesnesi (bölüm 2.2.2.3) alır veya ayarlar.

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


Görüntü hakkında bilgi belirten bir BitmapCoreHeader Nesnesi (bölüm 2.2.2.2) ya da bir BitmapInfoHeader Nesnesi (bölüm 2.2.2.3) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


Renk tablosunu tanımlayan RGBQuad Nesneleri (bölüm 2.2.2.20) ya da 16 bit işaretsiz tamsayılar içeren isteğe bağlı bir dizi alır veya ayarlar. Bu alanın boyutu ve içeriği, bu DeviceIndependentBitmap'i içeren metafile kaydı veya nesnesi ile DIBHeaderInfo alanındaki bilgilerden belirlenmelidir. Ek ayrıntılar için ColorUsage Enumerasyonu (bölüm 2.1.1.6) ve BitCount Enumerasyonu (bölüm 2.1.1.3) bakınız.

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


Renk tablosunu tanımlayan RGBQuad Nesneleri (bölüm 2.2.2.20) ya da 16 bit işaretsiz tamsayılar içeren isteğe bağlı bir dizi alır veya ayarlar. Bu alanın boyutu ve içeriği, bu DeviceIndependentBitmap'i içeren metafile kaydı veya nesnesi ile DIBHeaderInfo alanındaki bilgilerden belirlenmelidir. Ek ayrıntılar için ColorUsage Enumerasyonu (bölüm 2.1.1.6) ve BitCount Enumerasyonu (bölüm 2.1.1.3) bakınız.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


Görüntüyü tanımlayan bir bayt dizisini alır veya ayarlar. Bu verinin boyutu ve biçimi, DIBHeaderInfo alanındaki bilgilerle belirlenir.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


Görüntüyü tanımlayan bir bayt dizisini alır veya ayarlar. Bu verinin boyutu ve biçimi, DIBHeaderInfo alanındaki bilgilerle belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


Önbelleğe alınmış raster görüntüyü alır.

Değer: Önbelleğe alınmış görüntü.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


Önbelleğe alınmış raster görüntüyü ayarlar.

Değer: Önbelleğe alınmış görüntü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |


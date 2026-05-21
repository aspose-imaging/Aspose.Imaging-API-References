---
title: "BitmapInfoHeader"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BITMAPINFOHEADER'ı belirtir."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

BITMAPINFOHEADER'ı belirtir. İşletim Sistemi Desteği: Windows NT, 3.1x veya daha yeni. Özellikler: 16 bpp ve 32 bpp formatları ekler. RLE sıkıştırması ekler.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | Bitmap sıkıştırmasını alır. |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | Bitmap sıkıştırmasını ayarlar. |
| [getBitmapImageSize()](#getBitmapImageSize--) | Bitmap ham veri boyutunu bayt cinsinden alır. |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | Bitmap ham veri boyutunu bayt cinsinden ayarlar. |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | Yatay piksel çözünürlüğünü alır. |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | Yatay piksel çözünürlüğünü alır veya ayarlar. |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | Dikey piksel çözünürlüğünü alır veya ayarlar. |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | Dikey piksel çözünürlüğünü alır veya ayarlar. |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | Kullanılan palet renk sayısını alır. |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | Kullanılan palet renk sayısını alır veya ayarlar. |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | Önemli palet renk sayısını alır veya ayarlar. |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | Önemli palet renk sayısını alır veya ayarlar. |
| [getExtraBitMasks()](#getExtraBitMasks--) | Ek bit maskelerini alır veya ayarlar. |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | Ek bit maskelerini alır veya ayarlar. |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


Bitmap sıkıştırmasını alır.

**Returns:**
long - bitmap sıkıştırması.
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


Bitmap sıkıştırmasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | bitmap sıkıştırması. |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


Bitmap ham veri boyutunu bayt cinsinden alır.

**Returns:**
long - bitmap ham veri boyutu bayt cinsinden.
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


Bitmap ham veri boyutunu bayt cinsinden ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | bitmap ham veri boyutu bayt cinsinden. |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


Yatay piksel çözünürlüğünü alır.

**Returns:**
int - yatay piksel çözünürlüğü.
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


Yatay piksel çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | yatay piksel çözünürlüğü. |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


Dikey piksel çözünürlüğünü alır veya ayarlar.

**Returns:**
int - dikey piksel çözünürlüğü.
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


Dikey piksel çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | dikey piksel çözünürlüğü. |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


Kullanılan palet renk sayısını alır.

**Returns:**
long - kullanılan palet renk sayısı.
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


Kullanılan palet renk sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | kullanılan palet renk sayısı. |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


Önemli palet renk sayısını alır veya ayarlar.

**Returns:**
long - önemli palet renk sayısı.
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


Önemli palet renk sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | önemli palet renklerinin sayısı. |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


Ek bit maskelerini alır veya ayarlar. Yalnızca DIB başlığı BITMAPINFOHEADER olduğunda ve `BitmapCompression` `BitmapCompression.Bitfields` (RGB) veya `BitmapCompression.AlphaBitfields` (RGBA) olarak ayarlandığında bulunur.

**Returns:**
int[] - ek bit maskeleri.
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


Ek bit maskelerini alır veya ayarlar. Yalnızca DIB başlığı BITMAPINFOHEADER olduğunda ve `BitmapCompression` `BitmapCompression.Bitfields` (RGB) veya `BitmapCompression.AlphaBitfields` (RGBA) olarak ayarlandığında bulunur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | ek bit maskeleri. |


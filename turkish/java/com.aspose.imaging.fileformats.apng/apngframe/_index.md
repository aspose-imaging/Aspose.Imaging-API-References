---
title: "ApngFrame"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Tek sayfalı raster görüntülerden animasyonlu PNG APNG görüntü kareleri oluşturun, API'mizle."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

Tek sayfalı raster görüntülerden animasyonlu PNG (APNG) görüntü kareleri oluşturun, API'mizle. Animasyonu ve kare süresini sorunsuz bir şekilde ayarlayın, kare sayısını programlayın ve gama ile kontrast seviyelerini düzenleyin; böylece vizyonunuza göre etkileyici ve özelleştirilebilir animasyonlar elde edin.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getWidth()](#getWidth--) | Görüntünün genişliğini alır. |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini alır. |
| [getFrameTime()](#getFrameTime--) | Çerçeve süresini alır. |
| [setFrameTime(int value)](#setFrameTime-int-) | Kare süresini ayarlar. |
| [getFrameTop()](#getFrameTop--) | Çerçeve üst ötelemesini alır. |
| [getFrameLeft()](#getFrameLeft--) | Çerçeve sol ötelemesini alır. |
| [getDisposalMethod()](#getDisposalMethod--) | İmha yöntemini alır. |
| [hasTransparentColor()](#hasTransparentColor--) | Görselin şeffaf renk içerip içermediğini gösteren bir değer alır. |
| [hasAlpha()](#hasAlpha--) | Bu örneğin alfa içerip içermediğini gösteren bir değer al. |
| [getTransparentColor()](#getTransparentColor--) | Şeffaf rengi alır. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Görselin şeffaf renk içerip içermediğini gösteren bir değer. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Şeffaf renk. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Arka plan rengi içerip içermediğini gösteren bir değer alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengini alır. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Arka plan rengi içerip içermediğini gösteren bir değer. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Arka plan rengi. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Bu [use alpha blending] kullanılıp kullanılmadığını gösteren bir değeri alır. |
| [getFullFrame()](#getFullFrame--) | Tam çerçeveyi alır. |
| [cacheData()](#cacheData--) | Verileri önbelleğe alır ve temel `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

**Returns:**
int - görüntünün piksel başına bit sayısı.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini alır.

**Returns:**
int - görüntünün genişliği.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini alır.

**Returns:**
int - görüntünün yüksekliği.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Çerçeve süresini alır.

**Returns:**
int - çerçeve süresi.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


Kare süresini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | kare süresi. |

### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Çerçeve üst ötelemesini alır.

**Returns:**
int - çerçeve üst ötelemesi.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Çerçeve sol ötelemesini alır.

**Returns:**
int - çerçeve sol ötelemesi.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


İmha yöntemini alır.

**Returns:**
int - atık yöntemi.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Görselin şeffaf renk içerip içermediğini gösteren bir değer alır.

**Returns:**
boolean - görselin şeffaf renk içerip içermediğini gösteren bir değer.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu örneğin alfa içerip içermediğini gösteren bir değer al.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Şeffaf rengi alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Görselin şeffaf renk içerip içermediğini gösteren bir değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | görselin şeffaf renk içerip içermediğini gösteren bir değer. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Şeffaf renk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | şeffaf renk. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Arka plan rengi içerip içermediğini gösteren bir değer alır.

**Returns:**
boolean - arka plan rengine sahip olup olmadığını gösteren bir değer.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Arka plan rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Arka plan rengi içerip içermediğini gösteren bir değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | arka plan rengine sahip olup olmadığını gösteren bir değer. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Arka plan rengi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | arka plan rengi. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Bu [use alpha blending] kullanılıp kullanılmadığını gösteren bir değeri alır.

Değer: `true` eğer [use alpha blending] ise; aksi takdirde, `false`.

**Returns:**
boolean - [use alpha blending] kullanılıp kullanılmadığını gösteren bir değer.
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Tam çerçeveyi alır.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Verileri önbelleğe alır ve temel `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder.


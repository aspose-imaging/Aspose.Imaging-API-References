---
title: "WebPFrameBlock"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Webp blok açıcıları kaydını temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

Webp blok açıcıları kaydını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | Yeni bir `WebPFrameBlock` sınıfı örneği başlatır. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | Yeni bir `WebPFrameBlock` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini alır. |
| [getWidth()](#getWidth--) | Görüntünün genişliğini alır. |
| [hasAlpha()](#hasAlpha--) | Bu örneğin alfa içerip içermediğini gösteren bir değer alır. |
| [getDuration()](#getDuration--) | Çerçeve süresini alır veya ayarlar. |
| [setDuration(short value)](#setDuration-short-) | Çerçeve süresini alır veya ayarlar. |
| [getLeft()](#getLeft--) | Çerçeve konumunun solunu alır veya ayarlar. |
| [setLeft(short value)](#setLeft-short-) | Çerçeve konumunun solunu alır veya ayarlar. |
| [getTop()](#getTop--) | Çerçeve konumunun üstünü alır veya ayarlar. |
| [setTop(short value)](#setTop-short-) | Çerçeve konumunun üstünü alır veya ayarlar. |
| [getFrameTime()](#getFrameTime--) | Çerçeve süresini alır. |
| [getFrameTop()](#getFrameTop--) | Çerçeve üst ötelemesini alır. |
| [getFrameLeft()](#getFrameLeft--) | Çerçeve sol ötelemesini alır. |
| [getDisposalMethod()](#getDisposalMethod--) | İmha yöntemini alır. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | İmha yöntemini ayarlar. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Geçerli çerçevenin önceki çerçevenin alfa değerleriyle karıştırılıp karıştırılmadığını gösteren değeri alır. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | Geçerli çerçevenin önceki çerçevenin alfa değerleriyle karıştırılıp karıştırılmadığını gösteren değeri ayarlar. |
| [getFullFrame()](#getFullFrame--) | Tam çerçeveyi alır. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


Yeni bir `WebPFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


Yeni bir `WebPFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini alır.

**Returns:**
int - Görüntü yüksekliği.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini alır.

**Returns:**
int - Görüntü genişliği.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu örneğin alfa içerip içermediğini gösteren bir değer alır.

**Returns:**
boolean - bu örnek alfa içeriyorsa `true`; aksi takdirde `false`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Aktif TIFF çerçevesi alfa kanalına sahipse, tüm TIFF görüntüsü alfa kanalı olduğu kabul edilir.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, kullanılan kanallar: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, kullanılan kanallar: 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


Çerçeve süresini alır veya ayarlar.

**Returns:**
short - Süre.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


Çerçeve süresini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short | Süre. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


Çerçeve konumunun solunu alır veya ayarlar.

**Returns:**
short - Sol.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


Çerçeve konumunun solunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short | Sol. |

### getTop() {#getTop--}
```
public short getTop()
```


Çerçeve konumunun üstünü alır veya ayarlar.

**Returns:**
short - Üst.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


Çerçeve konumunun üstünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short | Üst. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Çerçeve süresini alır.

**Returns:**
int - çerçeve süresi.
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
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


İmha yöntemini ayarlar.

Değer: İmha yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | imha yöntemi. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Geçerli çerçevenin önceki çerçevenin alfa değerleriyle karıştırılıp karıştırılmadığını gösteren değeri alır.

Değer: `` bu çerçeve alfa harmanı kullanıyorsa; aksi takdirde, ``.

**Returns:**
boolean - geçerli çerçevenin önceki çerçevenin alfa değerleriyle karıştırılıp karıştırılmadığını gösteren değer.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


Geçerli çerçevenin önceki çerçevenin alfa değerleriyle karıştırılıp karıştırılmadığını gösteren değeri ayarlar.

Değer: `` bu çerçeve alfa harmanı kullanıyorsa; aksi takdirde, ``.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | geçerli çerçevenin önceki çerçevenin alfa değerleriyle karıştırılıp karıştırılmadığını gösteren değer. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Tam çerçeveyi alır.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.

---
title: "GifFrameBlock"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gif kare bloğu."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Gif kare bloğu.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | Yeni bir `GifFrameBlock` sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Blok uzantı etiketi. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | Görüntü tanımlayıcı boyutu. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | İlgili renk paletini alır. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | Bayrakları oluşturur. |
| [getFileFormat()](#getFileFormat--) | Dosya formatının bir değerini alır |
| [getWidth()](#getWidth--) | Görüntünün genişliğini alır. |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getFrameTime()](#getFrameTime--) | Süreyi alır. |
| [setFrameTime(int value)](#setFrameTime-int-) | Süreyi ayarlar. |
| [getInterlaced()](#getInterlaced--) | Bu `GifFrameBlock`'ın satır aralıklı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isInterlaced()](#isInterlaced--) | Bu görüntü örneğinin satır aralıklı olup olmadığını gösteren bir değeri alır. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Bu `GifFrameBlock`'ın satır aralıklı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isPaletteSorted()](#isPaletteSorted--) | Renk paletinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Renk paletinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | GIF çerçeve piksel başına bit sayısını alır veya ayarlar. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | GIF çerçeve piksel başına bit sayısını alır veya ayarlar. |
| [getLeft()](#getLeft--) | Sol görüntü konumunu alır veya ayarlar. |
| [setLeft(int value)](#setLeft-int-) | Sol görüntü konumunu alır veya ayarlar. |
| [getTop()](#getTop--) | Üst görüntü konumunu alır veya ayarlar. |
| [setTop(int value)](#setTop-int-) | Üst görüntü konumunu alır veya ayarlar. |
| [getFrameTop()](#getFrameTop--) | p'ye dönüştürür. |
| [getFrameLeft()](#getFrameLeft--) | Sol koordinatı alır. |
| [getDisposalMethod()](#getDisposalMethod--) | İmha yöntemini alır. |
| [getFlags()](#getFlags--) | Bayrakları alır veya ayarlar. |
| [setFlags(byte value)](#setFlags-byte-) | Bayrakları alır veya ayarlar. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Bu [use alpha blending] kullanılıp kullanılmadığını gösteren bir değeri alır. |
| [getControlBlock()](#getControlBlock--) | Bu blokla ilişkili grafik kontrol bloğunu alır. |
| [hasTransparentColor()](#hasTransparentColor--) | Çerçeve bloğunun şeffaf renk içerip içermediğini gösteren bir değeri alır. |
| [getTransparentColor()](#getTransparentColor--) | Çerçeve bloğunun şeffaf rengini alır. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Çerçeve bloğunun şeffaf renk içerip içermediğini gösteren bir değeri alır. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Çerçeve bloğunun şeffaf rengini alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengi için bir değer alır. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Arka plan rengi için bir değer ayarlar. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alır. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntünün parlaklığını ayarlar. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | İzin verilen farkla bir rengi diğerine değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [getFullFrame()](#getFullFrame--) | Tam çerçeveyi alır. |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Bu [RasterCachedImage](../../com.aspose.imaging/rastercachedimage) örneğinin boyutunu değiştirir. |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği. |
| yükseklik | int | Görüntü yüksekliği. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | int | Sol görüntü konumu. |
| üst | int | Üst görüntü konumu. |
| genişlik | int | Görüntünün genişliği. |
| yükseklik | int | Görüntü yüksekliği. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | int | Sol görüntü konumu. |
| üst | int | Üst görüntü konumu. |
| genişlik | int | Görüntünün Genişliği. |
| yükseklik | int | Görüntünün Yüksekliği. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |
| isPaletteSorted | boolean | `true` olarak ayarlanırsa renk paleti sıralanır. |
| isGifFrameInterlaced | boolean | `true` olarak ayarlanırsa GIF çerçevesi aralıklı olur. |
| bitsPerPixel | byte | Piksel başına bit. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve piksel ve palet verilerini başlatmak için görüntü. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve piksel ve palet verilerini başlatmak için görüntü. |
| sol | int | Sol görüntü konumu. |
| üst | int | Üst görüntü konumu. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve piksel ve palet verilerini başlatmak için görüntü. |
| sol | int | Sol görüntü konumu. |
| üst | int | Üst görüntü konumu. |
| isPaletteSorted | boolean | `true` olarak ayarlanırsa renk paleti sıralanır. |
| isGifFrameInterlaced | boolean | `true` olarak ayarlanırsa GIF çerçevesi aralıklı olur. |
| lzwCodeSize | byte | Piksel başına bit. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için akış. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için akış. |
| sol | int | Sol görüntü konumu. |
| üst | int | Üst görüntü konumu. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için akış. |
| sol | int | Sol görüntü konumu. |
| üst | int | Üst görüntü konumu. |
| isPaletteSorted | boolean | `true` olarak ayarlanırsa renk paleti sıralanır. |
| isGifFrameInterlaced | boolean | `true` olarak ayarlanırsa GIF çerçevesi aralıklı olur. |
| lzwCodeSize | byte | Piksel başına bit. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için yol. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için yol. |
| sol | int | Sol görüntü konumu. |
| üst | int | Üst görüntü konumu. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Yeni bir `GifFrameBlock` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için yol. |
| sol | int | Sol görüntü konumu. |
| üst | int | Üst görüntü konumu. |
| isPaletteSorted | boolean | `true` olarak ayarlanırsa renk paleti sıralanır. |
| isGifFrameInterlaced | boolean | `true` olarak ayarlanırsa GIF çerçevesi aralıklı olur. |
| lzwCodeSize | byte | Piksel başına bit. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


Blok uzantı etiketi.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


Görüntü tanımlayıcı boyutu.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


İlgili renk paletini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Çerçeve paleti. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Kapsayıcı paleti. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


Bayrakları oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |
| isPaletteSorted | boolean | `true` olarak ayarlanırsa renk paletindeki renkler sıralanır. |
| isGifFrameInterlaced | boolean | `true` olarak ayarlanırsa GIF çerçeve görüntüsü aralıklı olur. |

**Returns:**
byte - Oluşturulan bayraklar.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Dosya formatının bir değerini alır

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini alır.

**Returns:**
int - Görüntü genişliği.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini alır.

**Returns:**
int - Görüntü yüksekliği.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


Süreyi alır.

Değer: Milisaniye cinsinden süre.

**Returns:**
int - süre.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


Süreyi ayarlar.

Değer: Milisaniye cinsinden süre.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | süre. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Bu `GifFrameBlock`'ın satır aralıklı olup olmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - aralıklı ise `true`; aksi takdirde `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Bu görüntü örneğinin satır aralıklı olup olmadığını gösteren bir değeri alır.

Değer: bu görüntü örneği aralıklı ise `true`; aksi takdirde `false`.

**Returns:**
boolean - bu görüntü örneğinin aralıklı olup olmadığını gösteren bir değer.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Bu `GifFrameBlock`'ın satır aralıklı olup olmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` aralıklı ise; aksi takdirde `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Renk paletinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - renk paleti sıralı ise `true`; aksi takdirde `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Renk paletinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` renk paleti sıralı ise; aksi takdirde `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


GIF çerçeve piksel başına bit sayısını alır veya ayarlar.

**Returns:**
byte - GIF çerçeve piksel başına bit sayısı.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


GIF çerçeve piksel başına bit sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | GIF çerçeve piksel başına bit sayısı. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Sol görüntü konumunu alır veya ayarlar.

**Returns:**
int - Sol görüntü konumu.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Sol görüntü konumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Sol görüntü konumu. |

### getTop() {#getTop--}
```
public int getTop()
```


Üst görüntü konumunu alır veya ayarlar.

**Returns:**
int - Üst görüntü konumu.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Üst görüntü konumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Üst görüntü konumu. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


p'ye dönüştürür.

Değer: Üst.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


Sol koordinatı alır.

Değer: Sol.

**Returns:**
int - sol.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


İmha yöntemini alır.

**Returns:**
int - atık yöntemi.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


Bayrakları alır veya ayarlar.

**Returns:**
byte - Bayraklar.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Bayrakları alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | Bayraklar. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


Bu [use alpha blending] kullanılıp kullanılmadığını gösteren bir değeri alır.

Değer: `true` eğer [use alpha blending] ise; aksi takdirde, `false`.

**Returns:**
boolean - [use alpha blending] kullanılıp kullanılmadığını gösteren bir değer.
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


Bu blokla ilişkili grafik kontrol bloğunu alır.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Çerçeve bloğunun şeffaf renk içerip içermediğini gösteren bir değeri alır.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Çerçeve bloğunun şeffaf rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Çerçeve bloğunun şeffaf renk içerip içermediğini gösteren bir değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Çerçeve bloğunun şeffaf rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Arka plan rengi için bir değer alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Arka plan rengi için bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | arka plan rengi için bir değer. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasına yardımcı olabilir. Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yükleyip ardından [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) yöntemiyle kaydederseniz, 8 bit piksel başına çıkış PNG görüntüsü oluşur. Bunu önlemek ve PNG görüntüsünü 1 bit piksel başına kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları ikinci parametre olarak [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) yöntemine geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Görüntünün parlaklığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


İzin verilen farkla bir rengi diğerine değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldColorArgb | int | Değiştirilecek eski renk ARGB-değeri. |
| oldColorDiff | byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| newColorArgb | int | Eski rengi değiştirecek yeni renk ARGB-değeri. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. Not: Şeffaflığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorArgb | int | Şeffaf olmayan renkleri değiştirecek yeni renk ARGB-değeri. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


Tam çerçeveyi alır.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


Bu [RasterCachedImage](../../com.aspose.imaging/rastercachedimage) örneğinin boyutunu değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |


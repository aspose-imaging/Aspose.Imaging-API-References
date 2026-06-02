---
title: "DjvuPage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Djvu sayfa sınıfı"
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Djvu sayfa sınıfı
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | [page exported action] gerçekleştiğinde oluşur. |
| [PropertyChanged](#PropertyChanged) | Bir özellik değeri değiştiğinde oluşur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getParentImage()](#getParentImage--) | Sayfanın ait olduğu üst görüntüyü alır |
| [getWidth()](#getWidth--) | Sayfanın genişliğini alır |
| [getHeight()](#getHeight--) | Sayfanın yüksekliğini alır |
| [getImage()](#getImage--) | Görüntüyü alır. |
| [getThumbnailImage()](#getThumbnailImage--) | Sayfa için küçük resim görüntüsünü alır veya ayarlar |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | Sayfa için küçük resim görüntüsünü alır veya ayarlar |
| [getPageNumber()](#getPageNumber--) | Sayfa numarasını alır. |
| [isColor()](#isColor--) | Bu örneğin renkli olup olmadığını gösteren bir değeri alır. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | Dikdörtgen konumu için metni alır |
| [getForegroundImage()](#getForegroundImage--) | Sayfa için ön plan görüntüsünü alır |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | Sayfa için ön plan görüntüsünü alır |
| [getTextImage()](#getTextImage--) | Metin görüntüsünü alır. |
| [getTextImage(int subsample)](#getTextImage-int-) | Metin görüntüsünü alır. |
| [getBackgroundImage()](#getBackgroundImage--) | Arka plan görüntüsünü alır. |
| [extractThumbnailImage()](#extractThumbnailImage--) | Djvu sayfasından küçük resim görüntüsünü çıkarır. |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


[page exported action] gerçekleştiğinde oluşur.

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Bir özellik değeri değiştiğinde oluşur.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

Değer: Görüntünün piksel başına bit sayısı.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


Sayfanın ait olduğu üst görüntüyü alır

Değer: Belge.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Sayfanın genişliğini alır

Değer: Genişlik.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Sayfanın yüksekliğini alır

Değer: Yükseklik.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


Görüntüyü alır.

Değer: Görüntü.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


Sayfa için küçük resim görüntüsünü alır veya ayarlar

Değer: Küçük resim görüntüsü.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


Sayfa için küçük resim görüntüsünü alır veya ayarlar

Değer: Küçük resim görüntüsü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Sayfa numarasını alır.

Değer: Sayfa numarası.

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Çıktı şöyle görünebilir:
//Toplam sayfa sayısı: 2
//Etkin sayfa numarası:    1
//İlk sayfa numarası:     1
//Son sayfa numarası:      2
//--------------------------------------------------
//Sayfa numarası:     1
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
//--------------------------------------------------
//Sayfa numarası:     2
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


Bu örneğin renkli olup olmadığını gösteren bir değeri alır.

Değer: Bu örnek renk ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


Dikdörtgen konumu için metni alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Konum dikdörtgeni. |

**Returns:**
java.lang.String - Konumda bulunan metin
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


Sayfa için ön plan görüntüsünü alır

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


Sayfa için ön plan görüntüsünü alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alt örnekleme | int | Alt örnekleme. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


Metin görüntüsünü alır.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


Metin görüntüsünü alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alt örnekleme | int | Alt örnekleme. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


Arka plan görüntüsünü alır.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


Djvu sayfasından küçük resim görüntüsünü çıkarır.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.

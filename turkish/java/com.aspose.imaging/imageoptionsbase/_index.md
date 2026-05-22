---
title: "ImageOptionsBase"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü temel seçenekleri."
type: docs
weight: 62
url: /tr/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

Görüntü temel seçenekleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | Dışa aktarımda orijinal görüntü meta verilerini tutup tutmayacağına dair bir değer alır. |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | Dışa aktarımda orijinal görüntü meta verilerini tutup tutmayacağına dair bir değer. |
| [getXmpData()](#getXmpData--) | XMP meta veri konteynerini alır. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | XMP meta veri konteynerini ayarlar. |
| [getExifData()](#getExifData--) | Exif verilerini alır. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Exif verilerini ayarlar. |
| [getSource()](#getSource--) | Görüntünün oluşturulacağı kaynağı alır. |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| [getPalette()](#getPalette--) | Renk paletini alır. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Renk paletini ayarlar. |
| [getResolutionSettings()](#getResolutionSettings--) | Çözünürlük ayarlarını alır. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Çözünürlük ayarlarını ayarlar. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Vektör rasterleştirme seçeneklerini alır. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Vektör rasterleştirme seçeneklerini ayarlar. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu alır. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu ayarlar. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Çok sayfalı seçenekler |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | Çok sayfalı seçenekler |
| [getFullFrame()](#getFullFrame--) | Tam [full frame] olup olmadığını gösteren bir değeri alır. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Tam [full frame] olup olmadığını gösteren bir değeri ayarlar. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olay işleyicisini alır. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | İlerleme olay işleyicisini ayarlar. |
| [deepClone()](#deepClone--) | Bu örneği kopyalar. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Bu [Image](../../com.aspose.imaging/image) örneği destekliyor ve [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini uyguluyorsa, bir `metadata` örneği ayarlamaya çalışır. |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


Dışa aktarımda orijinal görüntü meta verilerini tutup tutmayacağına dair bir değer alır.

**Returns:**
boolean - dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağına dair bir değer.
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


Dışa aktarımda orijinal görüntü meta verilerini tutup tutmayacağına dair bir değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Dışa aktarırken orijinal görüntü meta verilerini tutup tutmayacağına dair bir değer. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP meta veri konteynerini alır.

Değer: XMP veri konteyneri.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP meta veri konteynerini ayarlar.

Değer: XMP veri konteyneri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | XMP meta veri konteyneri. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Exif verilerini alır.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Exif verilerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif verileri. |

### getSource() {#getSource--}
```
public Source getSource()
```


Görüntünün oluşturulacağı kaynağı alır.

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


Görüntünün oluşturulacağı kaynağı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | Görüntünün oluşturulacağı kaynak. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Renk paletini alır.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Renk paletini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |


**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// 100 x 100 piksel bir BMP görüntüsü oluştur.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Görüntünün sol üst köşesinden sağ alt köşesine doğru lineer degrade.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Tüm görüntüyü lineer degrade fırçası ile doldur.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece paletli bir görüntü
    // neredeyse paletlenmemiş bir görüntüden görsel olarak ayırt edilemez.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // 8-bit palet en fazla 256 renk içerir.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// Çıktı şu şekilde görünür:
// Paletli görüntü boyutu 11078 bayttir.
// Paletli olmayan görüntü boyutu 40054 bayttir.
```

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Çözünürlük ayarlarını alır.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Çözünürlük ayarlarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Bir BMP görüntüsünü dosyadan yükleyin.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Bazı görüntü işleme işlemleri yapın.

    // İstenen görüntü parametrelerini belirtmek için ek seçenekleri kullanın.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Kanal başına bit sayısı 8'dir.
    // Bir palet kullanıldığında, renk indeksi renk yerine görüntü verilerinde depolanır.
    saveOptions.setBitsPerChannel((byte) 8);

    // Sıkıştırmanın ilerleyici tipini ayarlayın.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Görüntü kalitesini ayarlayın. Değer 1 ile 100 arasındadır.
    saveOptions.setQuality(100);

    // Yatay/dikey çözünürlüğü inç başına 96 nokta olarak ayarlayın.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Kaynak görüntü renkliyse, gri tonlamaya dönüştürülecektir.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Çıktı boyutunu azaltmak için bir palet kullanın.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public VectorRasterizationOptions getVectorRasterizationOptions()
```


Vektör rasterleştirme seçeneklerini alır.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Vektör rasterleştirme seçeneklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Vektör rasterleştirme seçenekleri. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu alır.

Değer: Bellek boyutu ipucu, megabayt cinsinden. Pozitif olmayan değer, dahili tamponlar için bellek sınırlaması olmadığı anlamına gelir

**Returns:**
int - tampon boyutu ipucu, tüm dahili tamponlar için tanımlanan maksimum izin verilen boyut.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu ayarlar.

Değer: Bellek boyutu ipucu, megabayt cinsinden. Pozitif olmayan değer, dahili tamponlar için bellek sınırlaması olmadığı anlamına gelir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | tampon boyutu ipucu, tüm dahili tamponlar için tanımlanan maksimum izin verilen boyut. |

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


Çok sayfalı seçenekler

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


Çok sayfalı seçenekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Tam [full frame] olup olmadığını gösteren bir değeri alır.

Değer: `true` eğer [full frame]; aksi takdirde, `false`.

**Returns:**
boolean - [full frame] olup olmadığını gösteren bir değer.
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Tam [full frame] olup olmadığını gösteren bir değeri ayarlar.

Değer: `true` eğer [full frame]; aksi takdirde, `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [full frame] olup olmadığını gösteren bir değer. |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


İlerleme olay işleyicisini alır.

Değer: İlerleme olay işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


İlerleme olay işleyicisini ayarlar.

Değer: İlerleme olay işleyicisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | ilerleme olay işleyicisi. |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Yükleme/dışa aktarma işlemleri için ayrı işlem ilerleme olay işleyicilerinin örneği
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// STDOUT günlüğü şu şekilde görünebilir:
//        Yükleme olayı Başlatma : 1/4
//        Yükleme olayı Ön İşleme : 2/4
//        Yükleme olayı İşleme : 3/4
//        Yükleme olayı Sonlandırma : 4/4
//        Dışa aktarma olayı Başlatma : 1/4
//        Dışa aktarma olayı Ön İşleme : 2/4
//        Dışa aktarma olayı İşleme : 3/4
//        Dışa aktarma olayı Göreceli İlerleme : 1/1
//        Yükleme olayı Göreceli İlerleme : 1/1
//        Dışa aktarma olayı Sonlandırma : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Bu örneği kopyalar.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


Bu [Image](../../com.aspose.imaging/image) örneği destekliyor ve [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini uyguluyorsa, bir `metadata` örneği ayarlamaya çalışır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | metadata. |

**Returns:**
boolean - Doğru, eğer [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) örneği [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) örneğini destekliyor ve/veya uyguluyorsa; aksi takdirde, false.

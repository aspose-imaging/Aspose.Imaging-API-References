---
title: "ColorPaletteHelper"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Renk paleti manipülasyonu için yardımcı sınıf."
type: docs
weight: 29
url: /tr/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Renk paleti manipülasyonu için yardımcı sınıf.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | Yalnızca 2 renk içeren tek renkli bir renk paleti oluşturur. |
| [create4Bit()](#create4Bit--) | 4 bit renk paletini oluşturur. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | 4 bit gri tonlamalı paleti oluşturur. |
| [create8Bit()](#create8Bit--) | 8 bit renk paletini oluşturur. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | 8 bit gri tonlamalı paleti oluşturur. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | Tekdüzen 256 renkli paleti al. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | İlk görüntü renk değerlerinin üst bitlerinden oluşan 256 renkli paleti al. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | Belirtilen paletin şeffaf renkleri olup olmadığını belirler. |
| [createGrayscale(int bits)](#createGrayscale-int-) | Belirtilen bit sayısının gri tonlamalı paletini alır. |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Yalnızca 2 renk içeren tek renkli bir renk paleti oluşturur.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


4 bit renk paletini oluşturur.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


4 bit gri tonlamalı paleti oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| minIsWhite | boolean | `true` olarak ayarlanırsa palet beyaz renkle başlar, aksi takdirde siyah renkle başlar. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


8 bit renk paletini oluşturur.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


8 bit gri tonlamalı paleti oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| minIsWhite | boolean | `true` olarak ayarlanırsa palet beyaz renkle başlar, aksi takdirde siyah renkle başlar. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// Bir dosyaya kaydet
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// Çıktı görüntüsünün boyutunu azaltmak için piksel başına 8 bit kullan.
createOptions.setBitsPerPixel(8);

// Tüm gri tonları kapsayan standart 8-bit gri tonlamalı renk paletini ayarla.
// İşlenen görüntü yalnızca gri tonlamalı renkler içeriyorsa, onun paletlenmiş sürümü
// paletlenmemiş bir sürümden görsel olarak ayırt edilemez.
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// Sıkıştırma olmadan kaydet.
// Çıktı görüntüsünün boyutunu azaltmak için RLE-8 sıkıştırmasını da kullanabilirsiniz.
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// Yatay ve dikey çözünürlüğü 96 dpi olarak ayarla.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// 100 x 100 piksel boyutunda bir BMP görüntüsü oluştur ve bir dosyaya kaydet.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // Görüntüyü gri tonlamalı bir degrade ile doldur
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save();
} finally {
    image.dispose();
}
```

### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| entriesCount | int | İstenen giriş sayısı. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

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

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| entriesCount | int | İstenen giriş sayısı. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


Görüntünün bir paleti yoksa raster görüntüden renk paletini alır (görüntüyü paletler). Palet, daha iyi indeksli görüntü kalitesi için optimize edilecek veya PaletteMiningMethod.UseCurrentPalette kullanıldığında \"AS IS\" olarak alınacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| entriesCount | int | İstenen giriş sayısı. |
| paletteMiningMethod | int | Palet madenciliği yöntemi. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// PNG görüntüsünü yükler        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Dizinli renk türünü kullan
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Maksimum sıkıştırmayı kullan
    options.setCompressionLevel(9);
    // Mümkün olduğunca çok pikseli kapsayan en yakın 8-bit renk paletini al, böylece paletli bir görüntü
    // neredeyse paletlenmemiş bir görüntüden görsel olarak ayırt edilemez.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Çıktı dosya boyutu önemli ölçüde azaltılmalıdır
```

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef görüntünün sınırları. |
| entriesCount | int | İstenen giriş sayısı. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef görüntünün sınırları. |
| entriesCount | int | İstenen giriş sayısı. |
| useImagePalette | boolean | Ayarlanırsa, mevcutsa kendi görüntü paletini kullanacaktır |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef görüntünün sınırları. |
| entriesCount | int | İstenen giriş sayısı. |
| useImagePalette | boolean | Ayarlanırsa, mevcutsa kendi görüntü paletini kullanacaktır |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Yarı şeffaf alfa değişimi için arka plan rengi olarak kullanılacak renk. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


Görüntünün bir renk paleti yoksa raster görüntüden (görüntüyü paletler) renk paletini alır. Palet mevcutsa, hesaplamalar yerine bu kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef görüntünün sınırları. |
| entriesCount | int | İstenen giriş sayısı. |
| useImagePalette | boolean | Ayarlanırsa, mevcutsa kendi görüntü paletini kullanacaktır |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | Yarı şeffaf alfa değişimi için arka plan rengi olarak kullanılacak renk. |
| keepTransparency | boolean | Ayarlanırsa, görüntü renklerinin alfa kanal bitlerini dikkate alacaktır. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Tekdüzen 256 renkli paleti al.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Görüntü. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


İlk görüntü renk değerlerinin üst bitlerinden oluşan 256 renkli paleti al.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Görüntü. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Belirtilen paletin şeffaf renkleri olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Palet. |

**Returns:**
boolean - `true` eğer belirtilen palet şeffaf renkler içeriyorsa; aksi takdirde, `false`.
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


Belirtilen bit sayısının gri tonlamalı paletini alır. İzin verilen bit değerleri 1, 2, 4, 8'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bits | int | Bit sayısı. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.

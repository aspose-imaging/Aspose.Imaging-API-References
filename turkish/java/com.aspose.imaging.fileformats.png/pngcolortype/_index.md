---
title: "PngColorType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "PNG görüntü renk tipini temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

PNG görüntü renk tipini temsil eder.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Grayscale](#Grayscale) | Her pikselin bir gri ton örneği olduğu renk tipini temsil eder. |
| [Truecolor](#Truecolor) | Her pikselin bir R,G,B üçlüsü olduğu renk tipini temsil eder. |
| [IndexedColor](#IndexedColor) | Her pikselin bir palet indeksi olduğu renk tipini temsil eder; bir PLTE bölümü bulunmalıdır. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | Her pikselin bir gri ton örneği ve ardından bir alfa örneği olduğu renk tipini temsil eder. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | Her pikselin bir R,G,B üçlüsü ve ardından bir alfa örneği olduğu renk tipini temsil eder. |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

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

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Her pikselin bir gri ton örneği olduğu renk tipini temsil eder.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


Her pikselin bir R,G,B üçlüsü olduğu renk tipini temsil eder.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


Her pikselin bir palet indeksi olduğu renk tipini temsil eder; bir PLTE bölümü bulunmalıdır.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


Her pikselin bir gri ton örneği ve ardından bir alfa örneği olduğu renk tipini temsil eder.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


Her pikselin bir R,G,B üçlüsü ve ardından bir alfa örneği olduğu renk tipini temsil eder.


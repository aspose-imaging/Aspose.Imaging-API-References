---
title: "PaletteMiningMethod"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü paleti madencilik yöntemi"
type: docs
weight: 79
url: /tr/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

Görüntü paleti madencilik yöntemi
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | Görüntünün mevcut paletini kullan. |
| [ColorClustering](#ColorClustering) | Renk kümeleme yöntemi |
| [Histogram](#Histogram) | Histogram yöntemi |

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

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


Görüntünün mevcut paletini kullan.

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


Renk kümeleme yöntemi

### Histogram {#Histogram}
```
public static final int Histogram
```


Histogram yöntemi


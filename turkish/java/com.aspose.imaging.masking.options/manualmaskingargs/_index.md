---
title: "ManualMaskingArgs"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Manuel maskeleme yöntemi için belirtilen argümanları temsil eder."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

Manuel maskeleme yöntemi için belirtilen argümanları temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMask()](#getMask--) | Maskeyi oluşturan grafik şekil kümesini alır. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | Maskeyi oluşturan grafik şekil kümesini ayarlar. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
Bu örnek, bir raster görüntüyü görüntü maskesi ve manuel maske kullanarak birden fazla görüntüye nasıl ayıracağınızı gösterir. Görüntü maskesi, arka planı ön plan görüntü nesnelerinden ayırmak için kullanılan bir görüntü işleme tekniğidir.
``` java
String dir = "c:\\temp\\";

// Manuel bir maske tanımlayın.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// Manuel maskeyi ayarlayın.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Manuel kümeleme algoritmasını kullanın.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // Maskeyi oluşturan tüm şekiller tek bir şekle birleştirilecektir.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Alfa kanallı TrueColor PNG görüntüsünün beklenen maksimum boyutu.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // Her küme (segment) ayrı bir PNG dosyasına kaydedilecektir.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // Arka plan rengi turuncu olacaktır.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Maskenin uygulanacağı kaynak görüntünün alanı.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // ImageMasking sınıfının bir örneğini oluşturun.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Kaynak görüntüyü birkaç küme (segment) içine bölün.
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Maskleme sonucundan görüntüleri elde edin ve PNG olarak kaydedin.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Blue hills.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```

### ManualMaskingArgs() {#ManualMaskingArgs--}
```
public ManualMaskingArgs()
```


### getMask() {#getMask--}
```
public final GraphicsPath getMask()
```


Maskeyi oluşturan grafik şekil kümesini alır.

Değer: Maske.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


Maskeyi oluşturan grafik şekil kümesini ayarlar.

Değer: Maske.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | maskeyi oluşturan grafik şekillerin kümesi. |


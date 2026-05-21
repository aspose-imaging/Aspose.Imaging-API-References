---
title: "OtgRasterizationOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de rasterización de Otg"
type: docs
weight: 34
url: /es/java/com.aspose.imaging.imageoptions/otgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.OdRasterizationOptions](../../com.aspose.imaging.imageoptions/odrasterizationoptions)
```
public class OtgRasterizationOptions extends OdRasterizationOptions
```

Las opciones de rasterización de Otg
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OtgRasterizationOptions()](#OtgRasterizationOptions--) |  |
| [OtgRasterizationOptions(VectorRasterizationOptions imageOptions)](#OtgRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |

## Example: The following code snippet demonstrates how to convert an OTG image to PDF and other image formats.

``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";
String inputFilePath = dir + "VariousObjectsMultiPage.otg";
com.aspose.imaging.ImageOptionsBase[] options = {new com.aspose.imaging.imageoptions.PngOptions(), new com.aspose.imaging.imageoptions.PdfOptions()};
for (com.aspose.imaging.ImageOptionsBase saveOptions : options) {
    String extension = saveOptions instanceof com.aspose.imaging.imageoptions.PngOptions ? ".png" : ".pdf";
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath);
    try {
        com.aspose.imaging.imageoptions.OtgRasterizationOptions otgRasterizationOptions = new com.aspose.imaging.imageoptions.OtgRasterizationOptions();
        otgRasterizationOptions.setPageWidth(image.getWidth());
        otgRasterizationOptions.setPageHeight(image.getHeight());
        saveOptions.setVectorRasterizationOptions(otgRasterizationOptions);

        image.save(inputFilePath + extension, saveOptions);
    } finally {
        image.close();
    }
}
```

### OtgRasterizationOptions() {#OtgRasterizationOptions--}
```
public OtgRasterizationOptions()
```


### OtgRasterizationOptions(VectorRasterizationOptions imageOptions) {#OtgRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public OtgRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |


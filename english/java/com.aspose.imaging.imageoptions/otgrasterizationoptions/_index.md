---
title: OtgRasterizationOptions
second_title: Aspose.Imaging for Java API Reference
description: The Otg rasterization options
type: docs
weight: 32
url: /java/com.aspose.imaging.imageoptions/otgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.OdRasterizationOptions](../../com.aspose.imaging.imageoptions/odrasterizationoptions)
```
public class OtgRasterizationOptions extends OdRasterizationOptions
```

The Otg rasterization options
## Constructors

| Constructor | Description |
| --- | --- |
| [OtgRasterizationOptions()](#OtgRasterizationOptions--) |  |
| [OtgRasterizationOptions(VectorRasterizationOptions imageOptions)](#OtgRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |

## Example
The following code snippet demonstrates how to convert an OTG image to PDF and other image formats.
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
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |


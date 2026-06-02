---
title: "OdgRasterizationOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones de rasterización de Odg"
type: docs
weight: 33
url: /es/java/com.aspose.imaging.imageoptions/odgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.OdRasterizationOptions](../../com.aspose.imaging.imageoptions/odrasterizationoptions)
```
public class OdgRasterizationOptions extends OdRasterizationOptions
```

Las opciones de rasterización de Odg
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OdgRasterizationOptions()](#OdgRasterizationOptions--) |  |
| [OdgRasterizationOptions(VectorRasterizationOptions imageOptions)](#OdgRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |

## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgRasterizationOptions() {#OdgRasterizationOptions--}
```
public OdgRasterizationOptions()
```


### OdgRasterizationOptions(VectorRasterizationOptions imageOptions) {#OdgRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public OdgRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |


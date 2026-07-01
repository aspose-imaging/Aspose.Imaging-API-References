---
title: "OdgRasterizationOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "Odg 光栅化选项。"
type: docs
weight: 33
url: /zh/java/com.aspose.imaging.imageoptions/odgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.OdRasterizationOptions](../../com.aspose.imaging.imageoptions/odrasterizationoptions)
```
public class OdgRasterizationOptions extends OdRasterizationOptions
```

Odg 光栅化选项。
## 构造函数

| 构造函数 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |


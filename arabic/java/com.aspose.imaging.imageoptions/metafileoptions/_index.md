---
title: "MetafileOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات الأساس للملفات الوصفية."
type: docs
weight: 27
url: /ar/java/com.aspose.imaging.imageoptions/metafileoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public abstract class MetafileOptions extends ImageOptionsBase implements ICompressOptions
```

خيارات الأساس للملفات الوصفية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompress()](#getCompress--) | يحصل على قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة. |
| [setCompress(boolean value)](#setCompress-boolean-) | SSets قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة. |
### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


يحصل على قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة.

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


SSets قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة.

القيمة: `true` إذا كان مضغوطًا؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة. |


**Example: The following example shows how to convert a emf images to emz format**

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```


**Example: The following example shows how to convert a wmf images to wmz format**

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```


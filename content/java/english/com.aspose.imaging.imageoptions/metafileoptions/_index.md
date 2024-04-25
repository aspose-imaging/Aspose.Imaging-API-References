---
title: MetafileOptions
second_title: Aspose.Imaging for Java API Reference
description: The Metafiles base options.
type: docs
weight: 27
url: /com.aspose.imaging.imageoptions/metafileoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public abstract class MetafileOptions extends ImageOptionsBase implements ICompressOptions
```

The Metafiles base options.
## Methods

| Method | Description |
| --- | --- |
| [getCompress()](#getCompress--) | Gets a value indicating whether this \{@link \#\#Aspose\#FileFormats\#Core\#ImageOptions\} is compressed. |
| [setCompress(boolean value)](#setCompress-boolean-) | Sets a value indicating whether this \{@link \#\#Aspose\#FileFormats\#Core\#ImageOptions\} is compressed. |
### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Gets a value indicating whether this \{@link \#\#Aspose\#FileFormats\#Core\#ImageOptions\} is compressed.

Value: `true` if compressed; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this \{@link \#\#Aspose\#FileFormats\#Core\#ImageOptions\} is compressed.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Sets a value indicating whether this \{@link \#\#Aspose\#FileFormats\#Core\#ImageOptions\} is compressed.

Value: `true` if compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this \{@link \#\#Aspose\#FileFormats\#Core\#ImageOptions\} is compressed. |


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


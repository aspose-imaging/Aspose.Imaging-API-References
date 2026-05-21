---
title: "MetafileOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "De grundläggande alternativen för Metafiler."
type: docs
weight: 27
url: /sv/java/com.aspose.imaging.imageoptions/metafileoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public abstract class MetafileOptions extends ImageOptionsBase implements ICompressOptions
```

De grundläggande alternativen för Metafiler.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompress()](#getCompress--) | Hämtar ett värde som indikerar om den utgående bilden måste komprimeras. |
| [setCompress(boolean value)](#setCompress-boolean-) | SSätter ett värde som indikerar om den utgående bilden måste komprimeras. |
### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Hämtar ett värde som indikerar om den utgående bilden måste komprimeras.

Värde: `true` om komprimerad; annars `false`.

**Returns:**
boolean - ett värde som indikerar om den utgående bilden måste komprimeras.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


SSätter ett värde som indikerar om den utgående bilden måste komprimeras.

Värde: `true` om komprimerad; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om den utgående bilden måste komprimeras. |


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


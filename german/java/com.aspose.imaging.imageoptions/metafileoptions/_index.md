---
title: "MetafileOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Basisoptionen für Metadateien."
type: docs
weight: 27
url: /de/java/com.aspose.imaging.imageoptions/metafileoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public abstract class MetafileOptions extends ImageOptionsBase implements ICompressOptions
```

Die Basisoptionen für Metadateien.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompress()](#getCompress--) | Ruft einen Wert ab, der angibt, ob das Ausgabebild komprimiert werden muss. |
| [setCompress(boolean value)](#setCompress-boolean-) | Setzt einen Wert, der angibt, ob das Ausgabebild komprimiert werden muss. |
### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Ruft einen Wert ab, der angibt, ob das Ausgabebild komprimiert werden muss.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob das Ausgabebild komprimiert werden muss.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Setzt einen Wert, der angibt, ob das Ausgabebild komprimiert werden muss.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob das Ausgabebild komprimiert werden muss. |


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


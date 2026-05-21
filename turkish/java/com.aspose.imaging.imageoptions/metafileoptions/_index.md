---
title: "MetafileOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Metafiles temel seçenekleri."
type: docs
weight: 27
url: /tr/java/com.aspose.imaging.imageoptions/metafileoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public abstract class MetafileOptions extends ImageOptionsBase implements ICompressOptions
```

Metafiles temel seçenekleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompress()](#getCompress--) | Çıktı görüntüsünün sıkıştırılması gerekip gerekmediğini belirten bir değeri alır. |
| [setCompress(boolean value)](#setCompress-boolean-) | Çıktı görüntüsünün sıkıştırılması gerekip gerekmediğini belirten bir değeri ayarlar. |
### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Çıktı görüntüsünün sıkıştırılması gerekip gerekmediğini belirten bir değeri alır.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Returns:**
boolean - çıktının sıkıştırılması gerekip gerekmediğini belirten bir değer.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Çıktı görüntüsünün sıkıştırılması gerekip gerekmediğini belirten bir değeri ayarlar.

Değer: sıkıştırılmışsa `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | çıktının sıkıştırılması gerekip gerekmediğini belirten bir değer. |


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


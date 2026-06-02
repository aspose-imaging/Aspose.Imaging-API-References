---
title: "MetafileOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni di base dei Metafiles."
type: docs
weight: 27
url: /it/java/com.aspose.imaging.imageoptions/metafileoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public abstract class MetafileOptions extends ImageOptionsBase implements ICompressOptions
```

Le opzioni di base dei Metafiles.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompress()](#getCompress--) | Ottiene un valore che indica se l'immagine di output deve essere compressa. |
| [setCompress(boolean value)](#setCompress-boolean-) | Imposta un valore che indica se l'immagine di output deve essere compressa. |
### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Ottiene un valore che indica se l'immagine di output deve essere compressa.

Valore: `true` se compresso; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se l'immagine di output deve essere compressa.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Imposta un valore che indica se l'immagine di output deve essere compressa.

Valore: `true` se compresso; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se l'immagine di output deve essere compressa. |


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


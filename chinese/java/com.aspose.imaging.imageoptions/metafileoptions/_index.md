---
title: "MetafileOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "Metafiles 基础选项。"
type: docs
weight: 27
url: /zh/java/com.aspose.imaging.imageoptions/metafileoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public abstract class MetafileOptions extends ImageOptionsBase implements ICompressOptions
```

Metafiles 基础选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompress()](#getCompress--) | 获取一个值，指示输出图像是否必须压缩。 |
| [setCompress(boolean value)](#setCompress-boolean-) | 设置一个值，指示输出图像是否必须压缩。 |
### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


获取一个值，指示输出图像是否必须压缩。

值：如果已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean - 一个指示输出图像是否必须压缩的值。
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


设置一个值，指示输出图像是否必须压缩。

值：如果已压缩则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 一个指示输出图像是否必须压缩的值。 |


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


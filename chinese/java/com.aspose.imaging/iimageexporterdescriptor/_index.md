---
title: "IImageExporterDescriptor"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示图像导出器描述符。"
type: docs
weight: 132
url: /zh/java/com.aspose.imaging/iimageexporterdescriptor/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IImageDescriptor](../../com.aspose.imaging/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

表示图像导出器描述符。使用导出器描述符可以避免在内存中保存每个导出器实例以及多线程问题。
## 方法

| 方法 | 描述 |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | 确定图像导出器是否能够根据保存选项将指定图像导出为指定的图像格式。 |
| [createInstance()](#createInstance--) | 创建一个新的导出器实例。 |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


确定图像导出器是否能够根据保存选项将指定图像导出为指定的图像格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 要导出的图像。 |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | 选项基类。 |

**Returns:**
布尔型 - `true` 表示由此描述符创建的导出器能够将指定图像导出为指定的文件格式；否则为 `false`。
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


创建一个新的导出器实例。

**Returns:**
[IImageExporter](../../com.aspose.imaging/iimageexporter) - A new exporter instance.

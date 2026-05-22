---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageExportersRegistry 方法。创建首次找到的适用于指定保存选项和图像的导出器"
type: docs
weight: 30
url: /zh/net/aspose.imaging/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

创建第一个符合指定保存选项和图像的导出器。

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要导出的图像。 |
| 选项 | ImageOptionsBase | 用于导出的保存选项。 |

### 返回值

支持指定图像和保存选项的导出器，如果未找到此类导出器则为 null。

## 备注

第一个导出器实际上是最后注册的。

### 另请参见

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.Imaging](../../imageexportersregistry/)
* assembly [Aspose.Imaging](../../../)



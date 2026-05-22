---
title: "类 ImageExportersRegistry"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageExportersRegistry 类。表示图像导出器注册表。"
type: docs
weight: 9900
url: /zh/net/aspose.imaging/imageexportersregistry/
---
## ImageExportersRegistry class

表示图像导出器注册表。

```csharp
public static class ImageExportersRegistry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.imaging/imageexportersregistry/registeredexporterdescriptors/) { get; } | 获取已注册的导出器描述符。 |
| static [RegisteredFormats](../../aspose.imaging/imageexportersregistry/registeredformats/) { get; } | 获取已注册的导出格式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.imaging/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | 创建第一个符合指定保存选项和图像的导出器。 |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | 获取第一个符合指定保存选项和图像的受支持描述符。 |
| static [Register](../../aspose.imaging/imageexportersregistry/register/)(IImageExporterDescriptor) | 注册指定的图像导出器描述符。 |
| static [RegisterExporter](../../aspose.imaging/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | 注册导出器。 |
| static [UnregisterExporter](../../aspose.imaging/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | 注销导出器。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)



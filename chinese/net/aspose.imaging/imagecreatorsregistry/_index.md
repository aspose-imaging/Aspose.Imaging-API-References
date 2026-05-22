---
title: "类 ImageCreatorsRegistry"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageCreatorsRegistry 类。表示图像创建器注册表。"
type: docs
weight: 9890
url: /zh/net/aspose.imaging/imagecreatorsregistry/
---
## ImageCreatorsRegistry class

表示图像创建器注册表。

```csharp
public static class ImageCreatorsRegistry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.imaging/imagecreatorsregistry/registereddescriptors/) { get; } | 获取已注册的描述符。 |
| static [RegisteredFormats](../../aspose.imaging/imagecreatorsregistry/registeredformats/) { get; } | 获取已注册的图像创建格式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFirstSupportedCreator](../../aspose.imaging/imagecreatorsregistry/createfirstsupportedcreator/)(ImageOptionsBase) | 创建第一个找到的适用于指定条件的创建器。 |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imagecreatorsregistry/getfirstsupporteddescriptor/)(ImageOptionsBase) | 获取第一个找到的适用于指定条件的受支持描述符。 |
| static [Register](../../aspose.imaging/imagecreatorsregistry/register/)(IImageCreatorDescriptor) | 注册指定的图像创建器描述符。 |
| static [RegisterCreator](../../aspose.imaging/imagecreatorsregistry/registercreator/)(IImageCreatorDescriptor) | 注册创建器。 |
| static [UnregisterCreator](../../aspose.imaging/imagecreatorsregistry/unregistercreator/)(IImageCreatorDescriptor) | 注销创建器。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)



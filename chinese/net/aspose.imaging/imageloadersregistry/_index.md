---
title: "类 ImageLoadersRegistry"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageLoadersRegistry 类。表示图像加载器注册表"
type: docs
weight: 10210
url: /zh/net/aspose.imaging/imageloadersregistry/
---
## ImageLoadersRegistry class

表示图像加载器注册表。

```csharp
public static class ImageLoadersRegistry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.imaging/imageloadersregistry/registereddescriptors/) { get; } | 获取已注册的描述符。 |
| static [RegisteredFormats](../../aspose.imaging/imageloadersregistry/registeredformats/) { get; } | 获取已注册的图像加载格式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.imaging/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | 创建第一个找到的适用于指定 *stream* 并可选的 *loadOptions* 的加载器。 |
| static [GetFirstSupportedDescriptor](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | 获取第一个找到的适用于指定 *stream* 并可选的 *loadOptions* 的受支持描述符。 |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | 通过其类型名称获取第一个受支持的文件格式。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | 通过其类型名称获取第一个受支持的描述符。 |
| static [Register](../../aspose.imaging/imageloadersregistry/register/)(IImageLoaderDescriptor) | 注册指定的图像加载器描述符。 |
| static [RegisterLoader](../../aspose.imaging/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | 注册加载器。 |
| static [UnregisterLoader](../../aspose.imaging/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | 注销加载器。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)



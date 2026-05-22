---
title: "类 GifBlocksRegistry"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Gif.GifBlocksRegistry 类。表示 GIF 块打开器注册表"
type: docs
weight: 6790
url: /zh/net/aspose.imaging.fileformats.gif/gifblocksregistry/
---
## GifBlocksRegistry class

表示 gif 块打开器注册表。

```csharp
public static class GifBlocksRegistry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.imaging.fileformats.gif/gifblocksregistry/registereddescriptors/) { get; } | 获取已注册的描述符。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptor/)(Stream) | 获取第一个受支持的打开器描述符。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptorbytypename/)(string) | 通过其类型名称获取第一个受支持的描述符。 |
| static [LoadBlockByFirstSupportedDescriptor](../../aspose.imaging.fileformats.gif/gifblocksregistry/loadblockbyfirstsupporteddescriptor/)(Stream, IColorPalette) | 使用适用于指定 *stream* 的第一个找到的打开器加载 GIF 块。 |
| static [RegisterOpener](../../aspose.imaging.fileformats.gif/gifblocksregistry/registeropener/)(IGifBlockLoaderDescriptor) | 注册打开器。 |
| static [UnregisterOpener](../../aspose.imaging.fileformats.gif/gifblocksregistry/unregisteropener/)(IGifBlockLoaderDescriptor) | 注销打开器。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif/)
* assembly [Aspose.Imaging](../../)



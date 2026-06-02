---
title: "GifBlocksRegistry.LoadBlockByFirstSupportedDescriptor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifBlocksRegistry 方法。使用第一个找到的适用于指定流的打开器加载 gif 块"
type: docs
weight: 40
url: /zh/net/aspose.imaging.fileformats.gif/gifblocksregistry/loadblockbyfirstsupporteddescriptor/
---
## GifBlocksRegistry.LoadBlockByFirstSupportedDescriptor method

使用适用于指定 *stream* 的第一个找到的打开器加载 GIF 块。

```csharp
public static IGifBlock LoadBlockByFirstSupportedDescriptor(Stream stream, 
    IColorPalette containerPalette)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| containerPalette | IColorPalette | 容器调色板。 |

### 返回值

加载的 gif 块，若未找到打开器则为 null。

## 备注

第一个打开器实际上是最后注册的。

### 另请参见

* interface [IGifBlock](../../igifblock/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifBlocksRegistry](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry/)
* assembly [Aspose.Imaging](../../../)



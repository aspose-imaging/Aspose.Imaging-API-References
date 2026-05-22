---
title: "GifBlocksRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifBlocksRegistry 方法。获取第一个受支持的打开器描述符"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.gif/gifblocksregistry/getfirstsupporteddescriptor/
---
## GifBlocksRegistry.GetFirstSupportedDescriptor method

获取第一个受支持的打开器描述符。

```csharp
public static IGifBlockLoaderDescriptor GetFirstSupportedDescriptor(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |

### 返回值

gif 块打开器描述符，若此类流没有受支持的打开器描述符则为 null。

## 备注

第一个打开器实际上是最后注册的。

### 另请参见

* interface [IGifBlockLoaderDescriptor](../../igifblockloaderdescriptor/)
* class [GifBlocksRegistry](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifblocksregistry/)
* assembly [Aspose.Imaging](../../../)



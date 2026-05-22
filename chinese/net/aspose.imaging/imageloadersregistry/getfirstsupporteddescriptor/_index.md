---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageLoadersRegistry 方法。获取第一个找到的、适用于指定 stream 且可选 loadOptions 的受支持描述符"
type: docs
weight: 40
url: /zh/net/aspose.imaging/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

获取第一个找到的适用于指定 *stream* 并可选的 *loadOptions* 的受支持描述符。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

加载器描述符，支持指定的 *stream* 和 *loadOptions*，如果未找到此类描述符则返回 null。

## 备注

第一个加载器描述符实际上是最后注册的。

### 另请参见

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)



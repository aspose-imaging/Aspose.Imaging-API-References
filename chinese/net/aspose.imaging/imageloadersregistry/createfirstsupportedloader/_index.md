---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageLoadersRegistry 方法。创建第一个找到的、适用于指定 stream 且可选 loadOptions 的加载器"
type: docs
weight: 30
url: /zh/net/aspose.imaging/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

创建第一个找到的适用于指定 *stream* 并可选的 *loadOptions* 的加载器。

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

支持指定的 *stream* 和 *loadOptions* 的加载器，如果未找到此类加载器则返回 null。

## 备注

第一个加载器实际上是最后注册的。

### 另请参见

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)



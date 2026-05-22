---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Aspose.Imaging for .NET API 参考"
description: "IImageLoaderDescriptor 方法。确定图像加载器是否可以从指定的流读取新图像，并可选地使用 loadOptions"
type: docs
weight: 10
url: /zh/net/aspose.imaging/iimageloaderdescriptor/canload/
---
## IImageLoaderDescriptor.CanLoad method

确定图像加载器是否可以从指定的流读取新图像，并可选地使用 *loadOptions*。

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| streamContainer | StreamContainer | 流容器。 |
| loadOptions | LoadOptions | 由 *loadOptions* 指定的文件格式详细信息。*loadOptions* 可能为 null。 |

### 返回值

`true` 如果由此描述符创建的图像加载器可以从流中读取图像；否则为 `false`。

### 另请参见

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.Imaging](../../iimageloaderdescriptor/)
* assembly [Aspose.Imaging](../../../)



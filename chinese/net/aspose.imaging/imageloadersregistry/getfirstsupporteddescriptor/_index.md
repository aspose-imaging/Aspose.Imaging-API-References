---
title: GetFirstSupportedDescriptor
second_title: Aspose.Imaging for .NET API 参考
description: 获取第一个找到的适用于指定stream和可选loadOptions的支持描述符
type: docs
weight: 40
url: /zh/net/aspose.imaging/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

获取第一个找到的适用于指定*stream*和可选*loadOptions*的支持描述符。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

支持指定*stream*和*loadOptions*或如果没有找到这样的描述符，则返回 null。

### 评论

第一个加载器描述符实际上是最后一个注册的。

### 也可以看看

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor)
* class [LoadOptions](../../loadoptions)
* class [ImageLoadersRegistry](../../imageloadersregistry)
* 命名空间 [Aspose.Imaging](../../imageloadersregistry)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
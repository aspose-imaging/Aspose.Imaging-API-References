---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageLoadersRegistry 方法。根据类型名称获取第一个受支持的描述符"
type: docs
weight: 60
url: /zh/net/aspose.imaging/imageloadersregistry/getfirstsupporteddescriptorbytypename/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName method

通过其类型名称获取第一个受支持的描述符。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByTypeName(
    string descriptorTypeName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| descriptorTypeName | String | 描述符类型名称。 |

### 返回值

找到的第一个加载器描述符，若未找到则为 null。

## 备注

第一个加载器描述符实际上是最后注册的。

### 另请参见

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.Imaging](../../imageloadersregistry/)
* assembly [Aspose.Imaging](../../../)



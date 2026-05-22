---
title: "ImageCreatorsRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageCreatorsRegistry 方法。获取第一个找到的、适用于指定条件的受支持描述符"
type: docs
weight: 40
url: /zh/net/aspose.imaging/imagecreatorsregistry/getfirstsupporteddescriptor/
---
## ImageCreatorsRegistry.GetFirstSupportedDescriptor method

获取第一个找到的适用于指定条件的受支持描述符。

```csharp
public static IImageCreatorDescriptor GetFirstSupportedDescriptor(ImageOptionsBase imageOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 图像选项。 |

### 返回值

支持指定条件的创建者描述符；如果未找到此类描述符，则返回 null。

## 备注

第一个创建者描述符实际上是最后注册的。

### 另请参见

* interface [IImageCreatorDescriptor](../../iimagecreatordescriptor/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageCreatorsRegistry](../)
* namespace [Aspose.Imaging](../../imagecreatorsregistry/)
* assembly [Aspose.Imaging](../../../)


